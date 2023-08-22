<script>
export default {};
</script>

<template>
  <nav class="navbar navbar-expand-lg bg-body-tertiary">
    <div class="container">
      <a class="navbar-brand" href="#"
        ><img src="../assets/img/dc-logo.png" alt="logo"
      /></a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNavAltMarkup"
        aria-controls="navbarNavAltMarkup"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div
        class="collapse navbar-collapse justify-content-end"
        id="navbarNavAltMarkup"
      >
        <div class="navbar-nav text-uppercase">
          <a class="nav-link" href="#">Character</a>
          <a class="nav-link" href="#">Comics</a>
          <a class="nav-link" href="#">Movies</a>
          <a class="nav-link" href="#">Tv</a>
          <a class="nav-link" href="#">Games</a>
          <a class="nav-link" href="#">Collectibles</a>
          <a class="nav-link" href="#">Videos</a>
          <a class="nav-link" href="#">Fans</a>
          <a class="nav-link" href="#">News</a>
          <a class="nav-link" href="#">Shop</a>
        </div>
      </div>
    </div>
  </nav>
</template>

<style lang="scss" scoped>
a {
  font-weight: 700;
}

.nav-link:hover {
  background-color: #0c7cec;
  color: white;
}
</style>
