<script>
  import Image from "/Users/emonasantiago/Documents/choices-choices-the-tech-stack/Pinkuranail/src/images/logo.png";
</script>

<body>
  <header class="nav-header">
    <a href="/Online-Boeken" class="nav-link">Boeken</a>
    <div>
      <img src={Image} alt="My Image" />
    </div>
    <a href="/Over-ons" class="nav-link">Over ons</a>
  </header>
</body>

<style>
  .nav-header {
    background-color: var(--pink);
    height: 100px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 300px;
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
  }

  .nav-link:hover {
    color: var(--red);
  }

  @media only screen and (max-width: 375px) {
    .nav-header {
      padding: 0 20px;
    }
  }
</style>
