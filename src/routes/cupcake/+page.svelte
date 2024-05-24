<script>
  import Nav from "$lib/Nav.svelte"
</script>

<svelte:head>
  <title>Cupcake Ipsum</title>
</svelte:head>
<main>
  <div class="heading">
    <iframe src="https://giphy.com/embed/xUA7aPGFArAjWq7TC8" frameBorder="0" class="giphy-embed"></iframe>
    <h2>Yum Cupcake Ipsum</h2>
    <iframe src="https://giphy.com/embed/xUA7aPGFArAjWq7TC8" frameBorder="0" class="giphy-embed"></iframe>
  </div>
  <Nav />
  <p>Halvah liquorice apple pie jelly beans chupa chups candy icing tiramisu. Tart jelly jujubes gingerbread croissant biscuit. Chupa chups tart cheesecake lemon drops dragée chocolate bar dessert. Ice cream ice cream sugar plum jujubes dragée topping tiramisu croissant chocolate.</p>
  <p class="quote">"I use sugar to fill the hole in my soul."</p>
  <p>Jujubes tiramisu gingerbread cake donut chocolate bar tart marzipan pastry. Gingerbread jelly tootsie roll muffin bear claw muffin. Jelly-o fruitcake chocolate bar chupa chups chocolate sesame snaps candy. Sweet roll carrot cake cake jelly candy jujubes gummi bears jelly-o. Oat cake wafer chocolate bar sweet roll macaroon soufflé powder sugar plum tart.</p>
</main>

<style>
  .heading {
    display: flex;
    align-content: center;
    justify-content: space-around;
    background-color: #ffa9db74;
    margin-bottom: 3%;
  }
  h2 {
    padding-top: 3%;
    padding-bottom: 3%;
    font-size: 260%;
    font-family: "DM Serif Display", serif;
    transition: 2s;
  }
  h2:hover {
    transform: scale(1.05);
    font-size: 290%;
    transition: 2s;
  }
  .quote {
    background-color: white;
    font-weight: bolder;
    font-size: 200%;
    text-align: center;
    padding: 2%;
  }
  .quote:hover {
    background-color: pink;
    transition: 3s;
  }
  p {
    padding: 7%;
    font-family: "DM Serif Display", serif;
    font-size: 160%;
    background-color: #fff3c6;
    box-shadow: 5px 5px lrgba(209, 140, 21, 0.556);
    transition: 2s;
    margin: 5%;
    border-radius: 45px;
  }
  p:hover {
    transition: 2s;
    background-color: #ffd261;
    transform: scale(1.05);
  }
  iframe {
    width: 10%;
    border-radius: 40px;
  }
</style>
