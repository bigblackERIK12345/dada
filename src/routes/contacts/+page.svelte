<script lang="ts">
    import { Container, ListGroup, ListGroupItem,Image } from "@sveltestrap/sveltestrap";


</script>

<svelte:head>
    <title>О нас</title>
</svelte:head>

<Container>
    <h1>Наши контакты</h1>
    <ListGroup>
        <ListGroupItem>Тел:+7 499 343-53-23</ListGroupItem>
        <ListGroupItem>Шевченко 1723</ListGroupItem>
        <Image class="w-100" src="https://avatars.mds.yandex.net/i?id=f8c03f08d87e8536af4329c2ff8bf65e_l-5530893-images-thumbs&n=13"/>
    </ListGroup>
</Container>