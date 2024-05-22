<script>
  import Nav from "$lib/Nav.svelte"
</script>

<main>
  <div class="flagbackground">
    <div class="heading">
      <img src="poison.png" alt="" />
      <h2>Yar Pirate Ipsum</h2>
      <img src="poison.png" alt="" />
    </div>
    <Nav />
  </div>

  <div class="background">
    <p>Maroon square-rigged rope's end spirits fathom tackle bilge rat careen cackle fruit splice the main brace. Arr to go on account bilge six pounders smartly yo-ho-ho yawl tack boatswain maroon. Barque hogshead coffer Buccaneer loot fire ship Shiver me timbers Blimey salmagundi reef.</p>

    <p>Draft scuttle rigging shrouds blow the man down belaying pin cog fluke strike colors killick. Gibbet case shot hulk main sheet landlubber or just lubber fathom Corsair coxswain reef Jolly Roger. Parrel jib man-of-war run a shot across the bow bounty maroon dead men tell no tales Cat o'nine tails ye swing the lead.</p>
  </div>
</main>

<style>
  .heading {
    display: flex;
    align-items: center;
    justify-content: space-around;
  }

  .flagbackground {
    background-image: url("black-flag.png");
    background-size: cover;
    padding-top: 6%;
    padding-bottom: 6%;
  }
  h2 {
    color: #d9edff;
    font-size: 400%;
    font-family: hyper-scrypt;
    transition: 1.5s;
  }
  h2:hover {
    color: #880808;
  }

  .background {
    background-image: url("ship.gif");
    background-position: left;
    background-repeat: no-repeat;
    transition: 5s;
  }
  .background:hover {
    background-position: right;
    transition: 15s;
  }
  p {
    font-family: basteleur;
    background-color: rgba(255, 255, 255, 0.5);
    margin-left: 21%;
    margin-right: 21%;
    padding: 1%;
    margin-top: 8%;
    transition: 2s;
  }
  p:hover {
    /* font-size: larger; */
    background-color: whitesmoke;
    transform: scale(1.1);
    transition: 2s;
  }
  main {
    background-image: url("sea.gif");
    background-position: bottom;
    background-size: 50%;
    padding-bottom: 1.5%;
  }
</style>
