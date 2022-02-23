<template>
  <nav class="navbar navbar-expand-lg navbar-dark lila fixed">
    <a class="navbar-brand" href="#">
      Organic Garden
      <img src="../assets/vegetable.png" class="logo-navbar" />
    </a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
    <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
      <div class="navbar-nav">
        <router-link class="nav-item nav-link" exact-active-class="active" to="/">Home</router-link>
        <router-link class="nav-item nav-link" exact-active-class="active" to="about">About</router-link>
      </div>
    </div>
    
  </nav>
</template>
<script>

</script>
<style>
.logo-navbar {
  width: 35px;
}
.lila {
  background-color: #4d3863;
}
</style>