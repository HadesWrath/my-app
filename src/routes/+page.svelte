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

    let changeColor = () => {
        r = Math.floor(Math.random()*255)
        g = Math.floor(Math.random()*255);
        b = Math.floor(Math.random()*255);
    }

    
    setInterval(changeColor, 1/60)
    
</script>

<!-- HTML - Structure -->
<body style="background-color: rgb({r},{g},{b});">

</body>

