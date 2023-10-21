<script>
  import logo from "./assets/logo.png";
</script>

<main>
  <div class="container">
    <div>
      <a href="https://www.youtube.com/@CarrierLeather">
        <img src={logo} alt="Logo" class="centered" />
      </a>
      <div class="social">
        <!-- ... -->
      </div>
    </div>
  </div>
</main>

<style>
  .container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
  }

  .social {
    display: flex;
    justify-content: center;
  }

  img {
    width: 300px;
  }
</style>
