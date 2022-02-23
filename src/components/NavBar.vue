<template>
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <a class="navbar-brand" href="#">Organic Garden
    <img src='../assets/vegetable.png' class="logo-navbar">
  </a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
    <div class="navbar-nav">
      <router-link class="nav-item nav-link" exact-active-class="active" to='home'> Home</router-link>
      <router-link  class="nav-item nav-link" to='about'> About</router-link>

    </div>
  </div>
</nav>
</template>
<script>

</script>
<style>
.logo-navbar{
  width: 35px ;
}
</style>