<script lang="ts">
     import { GetToDos,Todos } from "$lib/store/ToDoStore";
    import { CardBody, Container, Card, Row, Col} from "@sveltestrap/sveltestrap";
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

<Container>
    <Row>
 {#each $Todos as todo}
 <Col md={2}>
 <Card>
    <CardBody>{todo.title}</CardBody>
 </Card>
</Col>
{/each}
</Row>
</Container>
