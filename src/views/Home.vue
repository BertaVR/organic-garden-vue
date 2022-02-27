<template>
  <div class="home">
    <UpperHeader />
    <NavBar />
    <main>
      <div class="principal">
      <HomePrincipal />
      </div>
    </main>
  </div>
</template>

<script>
// @ is an alias to /src
import NavBar from "@/components/NavBar.vue";
import UpperHeader from "@/components/UpperHeader.vue";
import HomePrincipal from "@/components/HomePrincipal.vue"

export default {
  name: "Home",
  components: {
    UpperHeader,
    NavBar,
    HomePrincipal,
    
},
};
</script>
<style>

</style>