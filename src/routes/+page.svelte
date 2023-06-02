<script>
  import Image from "/Users/emonasantiago/Documents/choices-choices-the-tech-stack/Pinkuranail/src/images/Hero-Nails.png";
</script>

<!-- Hero section -->
<section class="hero">
  <div class="hero-content">
    <h1 class="hero-title">PINKURA<br />NAIL<br /></h1>
    <p class="hero-text">
      Een uniek oog voor detail <br />
      en altijd op de hoogte van de nieuwste trends!
    </p>
    <a href="#" class="button">Check the nails !</a>
  </div>
  <div class="hero-image">
    <img src={Image} alt="My Image" />
  </div>
</section>

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
    height: auto;
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
  }
</style>
