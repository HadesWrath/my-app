<script>
  let animationNme = "temp";
</script>

<!-- html -->
<main style="--animationNme: {animationNme};">
  <div class="blur" />
  <!-- <ScrollingMap /> -->
  <button>
    <a href="/game">Play
  </button>
  <footer>Who's that Pokemon, made by Hayden Smith 2023</footer>
  
</main>


<style>

.blur {
  background: rgba(255, 255, 255, 0.2); 
  backdrop-filter: blur(8px); 
}
  main{
    background-position:-100px;
    background-size:200%;
    background-repeat:no-repeat;
    background-image:url('map segments/pewter city.png');
    animation: temp 30s infinite;
    animation-timing-function: linear;
    
    position:relative;
    flex-direction: column;
    display: flex;
    width:100%;
    height:100vh;
    justify-content: center;
    align-items: center;
  }
  footer{
    margin-top:auto;
    background-color: white;
    z-index: 2;
    width: 100%;
    text-align: center;
  }

  button{
    margin-top:auto;
    z-index: 2;
  }

  .blur{
    position:absolute;
    top:0;
    left:0;
    right:0;
    bottom:0;
  }

  /* Animations */
  @keyframes temp {
    0% { background-position: 0px;}
    50% { background-position: -1000px; }
    100% { background-position: 0px;}
  }
</style>