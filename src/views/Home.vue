<template>
  <div class="home">
    <UpperHeader />
    <NavBar />
    <main>
      <div class="content">
        <HomePrincipal />
        <HomeSecondary />
      </div>
    </main>
  </div>
</template>

<script>
// @ is an alias to /src
import NavBar from "@/components/NavBar.vue";
import UpperHeader from "@/components/UpperHeader.vue";
import HomePrincipal from "@/components/HomePrincipal.vue"
import HomeSecondary from "@/components/HomeSecondary.vue"

export default {
  name: "Home",
  components: {
    UpperHeader,
    NavBar,
    HomePrincipal,
    HomeSecondary
  },
};
</script>
<style>
@media (min-width: 1280px) {
  .content {
    display: grid;
    grid-template-rows: 1fr 500px;
  }
}
</style>