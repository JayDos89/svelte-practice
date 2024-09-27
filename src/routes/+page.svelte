<script>
    import Footer from '$lib/Footer.svelte';
    import dog1 from '$lib/pics/dog1.png';
</script>

<h1>Welcome to your library project...</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<Footer year={2023} pic={dog1} picname={"dog"}/>
<Footer year={1999}/>
<Footer />
<ooter />

<style>
    :global(*) {
        font-family: sans-serif;
    }
</style>
