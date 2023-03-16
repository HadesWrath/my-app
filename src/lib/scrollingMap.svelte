<!-- Javascript -->
<script>
    import { tweened } from 'svelte/motion';
    let styles = {

    }
    let mapX = tweened(0);
    let mapY = tweened(-200);
</script>

<!-- HTML -->
<main>
    <img src="fire red map.png" alt=""/>   
</main>

<!-- CSS -->
<style>
    main{
        height: 100vh;
        width: 100vw;
        padding: 0;
        border: 0;
        
    }

    img{
        overflow: hidden;
        object-fit: none;
        width: 100%;
        object-position: 0px 0px;
    }
</style>
