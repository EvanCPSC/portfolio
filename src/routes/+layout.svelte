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
        --bg: #00001a;
        --whblue: #ccccff;
        --liblue: #b3b3ff;
    }
    
    main {
        color: white;
        min-height: 100vh;
        background-color: var(--bg);
        size: 100%;
        overflow: auto;
    }
    
</style>