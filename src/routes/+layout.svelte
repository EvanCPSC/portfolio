<script>
    import Navbar from "$lib/components/navbar.svelte";
</script>
<Navbar />

<slot></slot>

<style>
    :root {
        --bg: #0f1f2d;
        --lired: #E85D75;
        --ligreen: #62C370;
        --liblue: #3E92CC;
        --dared: #783744;
        --dagreen: #356A42;
        --dablue: #235170;
    }
    
    body {
        color: white;
        background-color: var(--bg);
        size: 100%;
    }
    
</style>