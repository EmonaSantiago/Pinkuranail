<script>
  import images from "/Users/emonasantiago/Documents/choices-choices-the-tech-stack/Pinkuranail/src/images/Hero-Nails.png";
  import nail1 from "/Users/emonasantiago/Documents/choices-choices-the-tech-stack/Pinkuranail/src/images/nail1.png";
  import Reclame from "/Users/emonasantiago/Documents/choices-choices-the-tech-stack/Pinkuranail/src/images/Reclame.png";
</script>

<!-- Hero section -->
<section class="hero">
  <div class="hero-content">
    <h1 class="hero-title">PINKURA<br />NAIL<br /></h1>
    <p class="hero-text">
      Een uniek oog voor detail <br />
      en altijd op de hoogte van de nieuwste trends!
    </p>
    <a href="#nails" class="button">Check the nails !</a>
  </div>
  <div class="hero-image">
    <img src={images} alt="My Image" />
  </div>
</section>

<!-- Nails section -->
<section id="nails">
  <h2 class="nails-title">pinkuraNAIL</h2>
  <p class="nails-text">
    Van kleurrijke ontwerpen tot 3D-effecten en edelstenen, elke nagel kan een
    kunstwerk zijn. <br />
    Express je persoonlijkheid met unieke nagels die je stijl weerspiegelen.
  </p>

  <div class="image-collage">
    <img src={nail1} alt="Afbeelding 1" />
    <img src={nail1} alt="Afbeelding 1" />
    <img src={nail1} alt="Afbeelding 1" />
    <img src={nail1} alt="Afbeelding 1" />
    <img src={nail1} alt="Afbeelding 1" />
    <img src={nail1} alt="Afbeelding 1" />
  </div>
  <a href="#nails" class="button">Check the nails !</a>
</section>

<div class="container">
  <div class="left-content">
    <img class="reclame" src={Reclame} alt="My Image" width="100%" />

    <!-- Jouw tekst hier -->
  </div>
  <div class="right-content">
    <section id="boeken">
      <div class="boeken-content">
        <h2>Maak een afspraak!</h2>
        <p>Boek nu jouw unieke stijlvolle nagelafspraak!</p>
        <a href="#nails" class="boeken-button">ONLINE BOEKEN</a>
      </div>
    </section>
  </div>
</div>

<style>
  /* Hero-sectie */
  h1 {
    color: var(--red);
  }

  .hero {
    display: flex;
    /* align-items: center; */
    background-color: var(--l-pink);
  }

  .hero-content {
    flex: 1;
    padding: 100px;
  }

  .hero-title {
    font-size: 80px;
    font-weight: bold;
    margin-bottom: 10px;
  }

  .hero-text {
    margin-bottom: 20px;
  }

  .hero-image {
    text-align: center;
  }

  .hero-image img {
    max-width: 100%;
    height: 32em;
  }

  /* CSS-styling voor de linkknop */
  .button {
    display: inline-block;
    background-color: var(--red);
    color: #ffffff;
    text-decoration: none;
    padding: 10px 20px;
    border-radius: 4px;
    transition: background-color 0.3s ease;
  }

  .button:hover {
    background-color: var(--purple);
  }

  /* CSS-styling voor de sectie */
  #nails {
    text-align: center;
    padding: 40px;
    background-color: var(--pink);
  }

  .nails-title {
    font-size: 50px;
    font-weight: bold;
    margin-bottom: 10px;
    color: var(--red);
  }

  .nails-text {
    margin-bottom: 20px;
  }

  .image-collage {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-gap: 10px;
    justify-items: center;
    margin-bottom: 2em;
  }

  .image-collage img {
    max-width: 100%;
    height: auto;
  }

  /* Boeken section */
  .container {
    display: flex;
    flex-wrap: wrap;
  }

  .left-content {
    flex: 1;
  }

  .right-content {
    flex: 1;
  }

  @media (max-width: 768px) {
    .left-content,
    .right-content {
      flex: 100%;
    }
  }

  h2 {
    font-size: 20px;
  }
  #boeken {
    text-align: center;
    padding: 2em;
    height: 50vh;
  }

  .boeken-content {
    display: inline-block;
    background-color: var(--red);
    color: #ffffff;
    text-decoration: none;
    padding: 100px 200px;
    border-radius: 4px;
    transition: background-color 0.3s ease;
  }

  .boeken-button {
    display: inline-block;
    background-color: var(--purple);
    color: #ffffff;
    text-decoration: none;
    padding: 10px 20px;
    border-radius: 4px;
    transition: background-color 0.3s ease;
    margin: 2em;
  }

  .reclame {
    width: 20em;
    height: 20em;
    padding: 32px 32px;
  }
  /* Media query voor mobiele weergave */
  @media (max-width: 768px) {
    .hero {
      flex-direction: column;
    }

    .hero-content {
      padding: 1em;
    }

    .hero-title {
      font-size: 30px;
    }

    .hero-image img {
      max-width: 100%;
      height: auto;
    }

    #nails {
      height: 100vh;
    }

    .nails-title {
      font-size: 30px;
    }

    .boeken-content {
      padding: 20px 30px;
    }
  }
</style>
