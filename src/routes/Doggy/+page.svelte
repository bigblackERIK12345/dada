<script lang="ts">
     import { GetToDos } from "$lib/store/ToDoStore";
    import { Container } from "@sveltestrap/sveltestrap";
 import { onMount } from "svelte";
 onMount(()=>{
    async function FetchTodos() {
        await GetToDos();
    }
    FetchTodos();
})
</script>
<svelte:head>
    <title>Doggy</title>
</svelte:head>

<Container></Container>
