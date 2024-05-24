<script>
  import Header from "$lib/Header.svelte"
  import Footer from "$lib/Footer.svelte"
</script>

<svelte:head>
  <title>What's Ipsum Bro</title>
</svelte:head>
<Header />

<main>
  <h2>Lorem Ipsum with Flavour</h2>

  <p>What's Ipsum Bro is a lorem ipsum generator with a twist. Instead of the same old boring lorem ipsum, you can choose from a variety of flavours to spice up your placeholder text.</p>
  <div>
    <a href="pirate">
      <img src="pirate.png" alt="Pirate" />
    </a>
    <a href="cheese">
      <img src="cheese.png" alt="Cheese" />
    </a>
    <a href="cupcake">
      <img src="cupcake.png" alt="Cupcake" />
    </a>
    <a href="hipster">
      <img src="hipster.png" alt="Hipster" />
    </a>
  </div>
</main>

<Footer />

<style>
  h2 {
    text-align: center;
  }
  p {
    text-align: center;
  }
  div {
    display: flex;
    align-content: center;
    justify-content: space-around;
    padding-bottom: 10%;
  }
</style>
