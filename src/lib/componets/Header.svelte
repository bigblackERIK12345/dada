<script lang="ts">
    import {Nav,Navbar, NavbarBrand,NavItem,NavLink} from  '@sveltestrap/sveltestrap';
</script>
<Navbar>
<NavbarBrand href="/">Главная</NavbarBrand>

<Nav>
    <NavItem>
        <NavLink href="/about">О нас</NavLink>
</NavItem>
<NavItem>
    <NavLink href="/contacts">Контакты</NavLink>
</NavItem>
<NavItem>
    <NavLink href="/Doggy">Doggy</NavLink>
</NavItem>
</Nav>
</Navbar>