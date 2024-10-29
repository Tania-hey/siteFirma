<template>
  <div>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg fixed-top BgNavbar" id="navbar">
      <div class="container-fluid">
        <img class="card-img-top" src="../assets/img/LogoAlb.png" alt="Logo img" style="height: 8rem; width: 15rem;">
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav mx-auto">
            <li class="nav-item me-3">
              <a class="nav-link active link-light fs-5" aria-current="page" href="#">Despre noi</a>
            </li>
            <li class="nav-item me-3">
              <a class="nav-link link-light fs-5 link-opacity-100" href="#">Servicii</a>
            </li>
            <li class="nav-item me-3">
              <a class="nav-link link-light fs-5" href="#">Proiecte finalizate</a>
            </li>
            <li class="nav-item">
              <a class="nav-link link-light fs-5" href="#">Contact</a>
            </li>
          </ul>
          <!-- Retelele de socializare -->
          <div class="d-flex me-5">
            <a class="nav-link link-light" href="https://www.instagram.com/imperialdetailing.ro/" target="_blank" rel="noopener noreferrer">
              <i class="bi bi-instagram fs-3"></i>
            </a>
            <a class="nav-link mx-4 link-light" href="https://www.facebook.com/imperial.detailing.oradea?locale=ro_RO" target="_blank" rel="noopener noreferrer">
              <i class="bi bi-facebook fs-3"></i>
            </a>
            <a class="nav-link me-2 link-light" href="https://www.tiktok.com/@imperialdetailingoradea" target="_blank" rel="noopener noreferrer">
              <i class="bi bi-tiktok fs-3"></i>
            </a>
          </div>
        </div>
      </div>
    </nav>
    <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
      <ol class="carousel-indicators">
        <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
        <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
      </ol>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img class="d-block w-100 carousel-image " src="../assets/img/newGaraj.jpeg" alt="First slide">
        </div>
        <div class="carousel-item">
          <img class="d-block w-100 carousel-image " src="../assets/img/newGaraj.jpeg" alt="Second slide">
        </div>
        <div class="carousel-item">
          <img class="d-block w-100 carousel-image " src="../assets/img/newGaraj.jpeg" alt="Third slide">
        </div>
      </div>
      <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only"></span>
      </a>
      <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only"></span>
      </a>
    </div>
    <div class="overlay">
      <div>
        <div class="col-12">
          <h1>Bine ai venit la Imperial Detailing!</h1>
          <h4>Locul unde mașină ta își recăpăta strălucirea.</h4>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'SiteHeader',
  mounted() {
    window.addEventListener("scroll", this.handleScroll);
  },
  methods: {
    handleScroll() {
      const navbar = document.getElementById("navbar");
      if (window.scrollY > 100) {
        navbar.classList.add("BgNavbar");
      } else {
        navbar.classList.remove("BgNavbar");
      }
    }
  }
};
</script>

<style scoped>
/* Stiluri navbar */
.navbar {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  z-index: 1000;
  transition: background-color 0.3s ease;
}
.BgNavbar {
  background-color: rgba(112,112,112, 0.9); 
  height: 6.5rem;
}
.overlay {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: rgba(0, 0, 0, 0.5);
  display: flex;
  justify-content: center;
  align-items: center;
  height: 90vh;
}
.carousel-image {
  height: 90vh; 
  object-fit: cover; 
}

h1, h4 {
  color: #fff;
  text-align: center;
}
</style>
