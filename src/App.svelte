<script>
    import Logo from './Logo.svelte';
    import Navbar from './Navbar.svelte';
    import Hero from './Hero.svelte';
    import Footer from './Footer.svelte';
    import Services from './Services.svelte';
    import Projects from './Projects.svelte';
    import Customers from './Customers.svelte';
    import Contacts from './Contacts.svelte';
    import AboutUs from './AboutUs.svelte';
    import Product from './Product.svelte';

    console.log('%cWe\'re hiring! https://triarc-labs.com/#jobs', 'padding:20px')
</script>

<style>

</style>

<Hero></Hero>

<!--<Logo></Logo>-->
<!--<Navbar></Navbar>-->

<div class="section" id="services">
    <Services></Services>
</div>
<div class="section" id="projects">
    <Projects></Projects>
</div>
<div id="product">
    <Product></Product>
</div>
<div class="section" id="customers">
    <Customers></Customers>
</div>
<div class="section" id="aboutUs">
    <AboutUs></AboutUs>
</div>
<div class="section" id="contact">
    <Contacts></Contacts>
</div>
<Footer></Footer>

