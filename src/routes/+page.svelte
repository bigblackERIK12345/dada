<script lang="ts">
import { CardBody, CardHeader, CardImg, Col, Row, Card, CardText, Container, FormGroup, FormText, Button, Input, Form } from "@sveltestrap/sveltestrap";

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
                    <CardImg src="https://i6.photo.2gis.com/images/branch/0/30258560050713274_2361.jpg"/>
                    <CardText>Чертёнки</CardText>
                </CardBody>
            </Card>
        </Col>
        <Col>
            <Card>
                <CardHeader>Командир</CardHeader>
                <CardBody>
                <CardImg src="https://femuscleblog.wordpress.com/wp-content/uploads/2017/12/skinny-rich10-1.jpg"/>
                    <CardText>Миша Щуплый</CardText>
                </CardBody>
            </Card>
        </Col>

        <Col>
        <Card>
            <CardHeader>Символ</CardHeader>
            <CardBody>
                <CardImg src="https://avatars.mds.yandex.net/get-yapic/45848/enc-38cd8d84028180e1f374eae8b5da6460b4f074f2dc68035960352ba58fdfaef5/orig"/>
                    <CardText>Квадрат</CardText>
            </CardBody>
        </Card>
    </Col>
</Row>

<Form>
    <h1>Оставить заявку</h1>
    <FormGroup>
        <FormText>Ваш email</FormText>
        <Input type="email"/>
    </FormGroup>
    <Button color="success" class="w-100">Оставить заявку для вступления в клуб</Button>
</Form>

</Container>