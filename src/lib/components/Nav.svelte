<script>
  import Image from "/Users/emonasantiago/Documents/choices-choices-the-tech-stack/Pinkuranail/src/images/logo.png";
</script>

<header class="nav-header">
  <a href="/Online-Boeken" class="nav-link">Boeken</a>
  <div>
    <img src={Image} alt="My Image" />
  </div>
  <a href="/Over-ons" class="nav-link">Over ons</a>
</header>

<style>
  .nav-header {
    background-color: var(--pink);
    height: 100px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 300px;
    width: auto;
  }

  img {
    width: 10em;
    height: auto;
  }

  .nav-links {
    display: flex;
    justify-content: space-between;
  }

  .nav-link {
    text-decoration: none;
    color: white;
    margin: 0 10px;
    font-weight: bold;
    font-size: 1.5em;
  }

  .nav-link:hover {
    color: var(--red);
  }

  @media only screen and (max-width: 375px) {
    .nav-header {
      padding: 0 20px;
    }

    .nav-link {
      font-size: 16px;
    }
  }
</style>
