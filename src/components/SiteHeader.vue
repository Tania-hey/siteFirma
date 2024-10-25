<template>
  <nav class="navbar navbar-expand-lg navbar-light sticky-top">
    <div class="container-fluid">
      <img class="card-img-top me-3" src="../assets/img/LogoNegru.png" alt="Logo img" style="height: 5rem; width: 8rem;">
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav mx-auto"> <!-- Center the nav links -->
          <li class="nav-item me-3">
            <a class="nav-link active" aria-current="page" href="#">Despre noi</a>
          </li>
          <li class="nav-item me-3">
            <a class="nav-link" href="#">Servicii</a>
          </li>
          <li class="nav-item me-3">
            <a class="nav-link" href="#">Proiecte finalizate</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Contact</a>
          </li>
        </ul>

          <!-- Social Media Links -->
          <div class="d-flex">
          <a class="nav-link" href="https://www.instagram.com/imperialdetailing.ro/" target="_blank" rel="noopener noreferrer">
            <i class="bi bi-instagram"></i> <!-- Font Awesome Instagram Icon -->
          </a>
          <a class="nav-link mx-3" href="https://www.facebook.com/imperial.detailing.oradea?locale=ro_RO" target="_blank" rel="noopener noreferrer">
            <i class="bi bi-facebook"></i> <!-- Font Awesome Facebook Icon -->
          </a>
          <a class="nav-link me-2" href="https://www.tiktok.com/@imperialdetailingoradea" target="_blank" rel="noopener noreferrer">
            <i class="bi bi-tiktok"></i> <!-- Font Awesome TikTok Icon -->
          </a>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'SiteHeader',
}
</script>

<style scoped>

</style>
