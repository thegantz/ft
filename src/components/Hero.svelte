<script>
    import Infocard from "./Infocard.svelte";
    import Teamcard from "./Teamcard.svelte";
    import Logo from "./Logo.svelte";
    import Banner from "./Banner.svelte";
</script>

<div class="absolute sm:w-full min-h-screen md:bg-fixed bg-cover bg-center flex flex-col items-center py-10 md:bg-[url('/images/bg2.png')]">
    <Logo />
    <Banner />
    <Teamcard />
    <Infocard />
</div>