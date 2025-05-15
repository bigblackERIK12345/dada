<script lang="ts">
    import { Container, Card, Row, Col, CardHeader, CardLink, CardFooter, CardSubtitle, CardBody, CardImg, CardText} from "@sveltestrap/sveltestrap";


</script>

<svelte:head>
    <title>О нас</title>
</svelte:head>

<Container>
    <h1>О нас</h1>
    <Row>

        <Col>
            <Card>
                <CardHeader>Главный Спонсор нашего клуба</CardHeader>
                <CardBody>
                    <CardImg src="https://avatars.mds.yandex.net/i?id=853cbbcd4936f5c14df19100c7445b2475aafe46-9262149-images-thumbs&n=13"></CardImg>
                    <CardText>Сергей Каршков</CardText>
                    <CardLink href="/link">Ccылка</CardLink>
                </CardBody>
                <CardFooter>
                    <CardSubtitle>Компания 1xBet была создана в 2007 году</CardSubtitle>
                </CardFooter>
            </Card>
        </Col>
        <Col>
            <Card>
                <CardHeader>Второстепеный Спонсор нашего клуба</CardHeader>
                <CardBody>
                    <CardImg src="https://avatars.mds.yandex.net/i?id=0619e8bb5351f78973b25a8b515d2120a0def722-8316909-images-thumbs&n=13"></CardImg>
                    <CardText>Герман Попков</CardText>
                    <CardLink href="/link">Ccылка</CardLink>
                </CardBody>
                <CardFooter>
                    <CardSubtitle>Компания BetBoom была создана в 2011 году</CardSubtitle>
                </CardFooter>
            </Card>
        </Col>

            </Row>
</Container>