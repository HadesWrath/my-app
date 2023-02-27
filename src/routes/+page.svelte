<!-- CSS Styling -->
<style>

    body
    {
        margin:0;
        height: 100vh;
        width: 100vw;
    }
    
</style>

<!-- JS Functionality -->
<script>

    let r;
    let g;
    let b;
    let speed = 1;

    let changeColor = () => {
        r = Math.floor(Math.random()*255);
        g = Math.floor(Math.random()*255);
        b = Math.floor(Math.random()*255);
    }

    let updateSpeed = () => {speed++}
    
    let resetSpeed = {} => {speed = 0}

    let interval = null;

    
    let changeSpeed = () => {
        updateSpeed();        
        clearInterval(interval);
        interval = setInterval(changeColor, 1000/speed);    
    }

    
    
</script>

<!-- HTML - Structure -->
<body style="background-color: rgb({r},{g},{b});" on:click={changeSpeed}>

    <button on:click={resetSpeed}>
        button
    </button>
    <p>
        {speed}
    </p>
</body>




