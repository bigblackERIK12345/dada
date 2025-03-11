<script lang="ts">
    import Header from "$lib/componets/Header.svelte"
    import {Container,Styles}from "@sveltestrap/sveltestrap"
 let {children} = $props();
</script>

<Styles/>
<Container>
    <Header/>
    {@render children()}
</Container>