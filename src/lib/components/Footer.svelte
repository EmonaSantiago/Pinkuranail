<script>
  import Instagram from "/Users/emonasantiago/Documents/choices-choices-the-tech-stack/Pinkuranail/src/images/instagram-logo.png";
  import Tiktok from "/Users/emonasantiago/Documents/choices-choices-the-tech-stack/Pinkuranail/src/images/tiktok-logo.png";
  import House from "/Users/emonasantiago/Documents/choices-choices-the-tech-stack/Pinkuranail/src/images/home.png";
</script>

<body>
  <footer class="footer">
    <div class="footer-icons">
      <a href="#" class="footer-icon">
        <img src={Instagram} alt="My Image" />
      </a>
      <a href="#" class="footer-icon">
        <img src={Tiktok} alt="My Image" />
      </a>
      <a href="#" class="footer-icon">
        <img src={House} alt="My Image" />
      </a>
    </div>
  </footer>
</body>

<style>
  body {
    position: relative;
    /* min-height: 100vh; */
    margin: 0;
    padding: 0;
  }

  .content {
    padding-bottom: 60px; /* Adjust this value to match footer height */
  }

  .footer {
    /* position: absolute; */
    bottom: 0;
    left: 0;
    width: 100%;
    background-color: var(--pink);
    height: 100px;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .footer-icons {
    display: flex;
  }

  .footer-icon {
    text-decoration: none;
    color: #333333;
    margin: 0 20px;
    display: flex;
    align-items: center;
  }

  .footer-icon img {
    width: 20px;
    height: 20px;
    margin-right: 5px;
  }
</style>
