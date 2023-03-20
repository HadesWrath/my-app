<script>
    import './style.css'
    import Poketitle from '$lib/poketitle.svelte';
    import ScrollingMap from '$lib/scrollingMap.svelte';

    //(gotoGame) => ; need to define function that switches to the game page 
</script>

<Poketitle />
<ScrollingMap />
<button on:click={gotoGame}>Play</button>


<footer>
    Whos that Pokemon @ Hayden Smith 2023
</footer>

