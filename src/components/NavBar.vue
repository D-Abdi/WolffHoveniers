<template>
  <nav class="navbar navbar-expand-lg" style="background-color: white!important">
    <div class="container">
      <a class="navbar-brand" href="#"><img src="../assets/logo.png" alt="Wolff Hovenier en Bestrating logo"
                                            style="height: 75px"/></a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
              aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <ul class="nav justify-content-end">
        <li class="nav-item">
          <a class="nav-link text-black text-decoration-none navLink active" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle text-black text-decoration-none navLink" data-bs-toggle="dropdown" href="#" role="button" aria-expanded="false">Werkzaamheden</a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Tuinonderhoud</a></li>
            <li><a class="dropdown-item" href="#">Beschutting</a></li>
            <li><a class="dropdown-item" href="#">Bestrating</a></li>
            <li><a class="dropdown-item" href="#">Grond verzet</a></li>
          </ul>
        </li>
        <li class="nav-item">
          <a class="nav-link text-black text-decoration-none navLink" href="#">Over ons</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-black  text-decoration-none navLink" href="#">Contact</a>
        </li>
      </ul>
  </div>
  </nav>
</template>

<script>
export default {
  name: 'NavBar',
}
</script>

<style>

</style>
