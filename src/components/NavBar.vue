<template>
  <nav class="navbar navbar-expand-lg navbar-dark verde sticky-top">
    <div class="container-fluid">
      <router-link class="navbar-brand" to="/">
        Organic Garden
        <img src="../assets/vegetable.png" alt="logo" class="logo-navbar" />
      </router-link>
      <form class="form-inline">
        <a href="#" class="toRight nav-item">
          <i class="fa fa-arrow-circle-up arrowInBar" aria-hidden="true"></i>
        </a>
      </form>
      <button
        class="navbar-toggler"
        style="margin-right:5px !important;"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse top_nav" id="navbarSupportedContent">
        <div class="navbar-nav">
          <router-link class="nav-item nav-link" exact-active-class="active" to="/">Home</router-link>
          <router-link class="nav-item nav-link" exact-active-class="active" to="about">About</router-link>
          <a href="#" class="nav-link arrowDropdown">
            <span class="nav-link">
              Go up
              <i class="fa fa-arrow-circle-up" aria-hidden="true"></i>
            </span>
          </a>
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
  background-color: #204b1f;
}
.navbar-brand {
  padding-left: 20px;
}

.toRight {
  position: absolute;
  right: 85px;
  top: 17px;
}
.fa-arrow-circle-up {
  font-size: 1.7em;
  color: rgb(135, 201, 126);
}

@media (max-width: 385px) {
  .arrowInBar {
    display: none;
  }
}
@media (min-width: 386px) {
  .arrowDropdown {
    display: none;
  }
}
</style>