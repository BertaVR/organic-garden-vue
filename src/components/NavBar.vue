<template>
  <nav class="navbar navbar-expand-lg navbar-dark verde fixed">
    <a class="navbar-brand" href="#">
      Organic Garden
      <img src="../assets/vegetable.png" alt="logo" class="logo-navbar" />
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
.verde {
  background-color: #255a23;
}
.navbar{padding-left:20px}
</style>