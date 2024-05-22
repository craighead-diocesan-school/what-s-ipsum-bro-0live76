<script>
  import Nav from "$lib/Nav.svelte"
</script>

<main>
  <div class="heading">
    <img src="cheese.png" alt="" />
    <h2>Pee-YOO Cheese Ipsum</h2>
    <img src="cheese.png" alt="" />
  </div>
  <Nav />
  <div class="body">
    <p>Cheesy grin parmesan taleggio. Brie boursin pecorino cheesy feet taleggio hard cheese roquefort when the cheese comes out everybody's happy. St. agur blue cheese port-salut bocconcini cheesecake rubber cheese mozzarella stilton cheese strings. Bocconcini.</p>
    <iframe src="https://giphy.com/embed/SkmOdeRVdFZTi" width="480" height="349" frameBorder="0" class="giphy-embed" allowFullScreen></iframe>

    <p>Fromage the big cheese camembert de normandie. Cut the cheese gouda brie the big cheese when the cheese comes out everybody's happy squirty cheese cut the cheese gouda. Boursin cottage cheese cheeseburger camembert de normandie cheese slices goat port-salut danish fontina. Emmental caerphilly cream cheese mozzarella camembert de normandie cheesy feet.</p>
  </div>
</main>

<style>
  h2 {
    text-align: center;
    font-size: 500%;
    padding-top: 3%;
    font-family: "Jacquard 24", system-ui;
  }
  p {
    font-size: 180%;
    background-color: rgba(255, 230, 4, 0.434);
    transition: 1s;
    border-radius: 30px;
    padding: 3%;
    font-family: "Jacquard 24", system-ui;
  }
  p:hover {
    transition: 1s;
    background-color: rgb(255, 230, 4);
  }
  iframe {
    padding-left: 23%;
  }
  .heading {
    display: flex;
    align-content: center;
    justify-content: space-around;
  }
  .body {
    padding-top: 8%;
    padding-left: 15%;
    padding-right: 15%;
  }
</style>
