<section>
  <img src="pokemon silhouettes/pikachu.png"/>
  <img src="pokemon silhouettes/sandslash.png"/>
  <h1>Who's That Pokemon?</h1>
  <img src="pokemon silhouettes/scyther.png"/>
  <img src="pokemon silhouettes/mew.png"/>
</section>

<style>
  @font-face {
    font-family: Pokemon s;
    src: url("/fonts/pokemon_solid-webfont.woff") format("woff");
    src: url("/fonts/pokemon_solid-webfont.woff2") format("woff2");
    font-weight: normal;
    font-style: normal;
  }

  h1 {
    color: white;
    letter-spacing: .2rem;
    -webkit-text-stroke-color: black;
    -webkit-text-stroke-width: 1px;
    font-family: "Pokemon s";
    margin: 0 auto;
    font-size: 50px;
  }

  section{
    background-color: rgb(240, 64, 55);
    display: flex;
    flex-basis: 0;
    position: fixed;
    z-index: 2;
    width: 100%;
    top:0;
    justify-content: space-evenly;
  }

  img{
    object-fit: scale-down;
    width: 4%;
    padding: 0 2%;
  }
</style>
