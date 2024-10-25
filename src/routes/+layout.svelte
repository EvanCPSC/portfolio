<script>
    import Navbar from "$lib/components/navbar.svelte";
</script>

<main>
    <Navbar />
    <slot />
</main>

<svelte:head>
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
</svelte:head>

<style>
    :global(body) { margin: 0; padding: 0; }
    :root {
        --bg: #0f1f2d;
        --lired: #E85D75;
        --ligreen: #62C370;
        --liblue: #3E92CC;
        --dared: #783744;
        --dagreen: #356A42;
        --dablue: #235170;
    }
    
    main {
        color: white;
        min-height: 100vh;
        background-color: var(--bg);
        size: 100%;
    }
    
</style>