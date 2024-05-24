<script>
  import Nav from "$lib/Nav.svelte"
</script>

<main>
  <h2>You Probably Haven't Heard of Hipster Ipsum</h2>
  <Nav />

  <div class="columns">
    <div class="column">
      <img src="hipsterman.jpeg" alt="Hipster Man" />
      <p class="italic">Hallo! My name is Franz Prätentiöser, and I like lentil-based food!</p>
    </div>
    <div class="column text">
      <p>Fingerstache tofu pickled vibecession kitsch lyft blackbird spyplane vegan craft beer keytar banh mi thundercats. Hashtag heirloom vape scenester paleo hexagon. Blackbird spyplane pok pok DIY heirloom scenester food truck kale chips pabst, bitters raw denim artisan waistcoat seitan freegan.</p>
      <p>Put a bird on it vibecession fashion axe YOLO asymmetrical. VHS photo booth listicle fam truffaut subway tile yr cred chicharrones semiotics biodiesel green juice microdosing whatever. Truffaut praxis PBR and B tattooed street art. Prism jean shorts pickled vegan. Vegan praxis cronut kitsch pop-up. Letterpress street art mlkshk marxism.</p>
    </div>
  </div>
</main>

<style>
  h2 {
    margin-left: 5%;
    padding-top: 3%;
    padding-bottom: 3%;
    font-size: 350%;
    font-family: "Danfo", serif;
    transition: 4s;
  }
  h2:hover {
    color: brown;
    transition: 3s;
  }

  p {
    font-size: 150%;
    padding: 3%;
  }
  img {
    width: 50%;
    margin-left: 30%;
    transition: 2s;
  }
  img:hover {
    transform: scale(1.1);
    transition: 2s;
  }
  .columns {
    padding-top: 5%;
    display: flex;
    align-content: center;
  }
  .column {
    width: 60%;
    margin-left: 3%;
    margin-right: 3%;
  }
  .italic {
    font-style: italic;
  }
  .text {
    transition: 2s;
    background-color: #ffe595c0;
  }
  .text:hover {
    background-color: rgb(252, 188, 93);
    transform: scale(1.1);
    transition: 2s;
    border-radius: 15px;
  }
</style>
