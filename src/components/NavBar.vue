<template>
  <nav class="navbar navbar-expand-lg navbar-dark verde sticky-top">
      <div class="container-fluid">

    <router-link class="navbar-brand" to="/">
      Organic Garden
      <img src="../assets/vegetable.png" alt="logo" class="logo-navbar" />
   </router-link>

    <button class="navbar-toggler" style="margin-right:5px !important;" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent">
                <span class="navbar-toggler-icon"></span>
              </button>
    <div class="collapse navbar-collapse top_nav" id="navbarSupportedContent">
      <div class="navbar-nav">
        <router-link class="nav-item nav-link" exact-active-class="active" to="/">Home</router-link>
        <router-link class="nav-item nav-link" exact-active-class="active" to="about">About</router-link>
      </div>
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
.navbar-brand{padding-left:20px}


</style>