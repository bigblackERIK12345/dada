<script lang="ts">
    import { CardBody, CardHeader, CardImg, Col, Row, Card, CardText, Container, } from "@sveltestrap/sveltestrap";


</script>

<svelte:head>
    <title>О нас</title>
</svelte:head>

<Container>
    <Row>
        <Col>
            <Card>
                <CardHeader>Участники</CardHeader>
                <CardBody>
                    <CardImg src="">
                        <CardText></CardText>
                </CardBody>
            </Card>
        </Col>
    </Row>

    <Col>
        <Card>
            <CardHeader>Командир</CardHeader>
            <CardBody>
                <CardImg src="https://arbuztoday.ru/wp-content/uploads/2023/08/width.jpeg">
                    <CardText></CardText>
            </CardBody>
        </Card>
    </Col>

    <Col>
        <Card>
            <CardHeader>Символ</CardHeader>
            <CardBody>
                <CardImg src="https://avatars.mds.yandex.net/get-yapic/45848/enc-38cd8d84028180e1f374eae8b5da6460b4f074f2dc68035960352ba58fdfaef5/orig">
                    <CardText></CardText>
            </CardBody>
        </Card>
    </Col>
</Container>