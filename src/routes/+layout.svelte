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
        --bg: #1c2950;
        --liligreen: #C7F9CC;
        --lilidegreen: #C9E4CA;
        --ligreen: #80ED99;
        --lidegreen: #87BBA2;
        --liblue: #38A3A5;
        --lideblue: #55828B;
        --dagreen: #57CC99;
        --dadegreen: #3B6064;
        --dablue: #22577A;
        --dadeblue: #364958;
    }
    
    main {
        color: white;
        min-height: 100vh;
        background-color: var(--bg);
        size: 100%;
    }
    
</style>