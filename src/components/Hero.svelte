<script>
    import Infocard from "./Infocard.svelte";
    import Navbar from "./Navbar.svelte";
    import Teamcard from "./Teamcard.svelte";
    import Logo from "./Logo.svelte";
    import Banner from "./Banner.svelte";
</script>

<div class="absolute w-full min-h-screen md:bg-fixed bg-cover bg-center flex flex-col items-center py-10" style="background-image:url(/src/public/images/bg.png)">
    <Logo />
    <Banner />
    <Teamcard />
    <Infocard />
</div>