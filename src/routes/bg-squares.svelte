

    <div class="topnav"></div>
    <div class="leftnav"></div>
    <div class="socials"></div>


<style>
    :root {
        --bg: #0D1821;
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
    .topnav {
        z-index: -3;
        width: 30em;
        height: 7em;
        position: fixed;
        background-color: var(--liblue);
        top: 0;
        right: 0;
    }
    .leftnav {
        z-index: -3;
        width: 18em;
        height: 18em;
        rotate: 45deg;
        position: fixed;
        background-color: var(--lired);
        top: 14em;
        left: -10em;
    }
    .socials {
        z-index: -3;
        width: 30em;
        height: 30em;
        rotate: 45deg;
        position: fixed;
        background-color: var(--ligreen);
        bottom: -15em;
        right: -15em;
    }
</style>