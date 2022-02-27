<template>
  <div class="home">
    <header>
    <UpperHeader />
    <NavBar />
    </header>
    <main>
      <div class="content">
        <HomePrincipal />
        <HomeSecondary />
      </div>
    </main>
    <MyFooter />
  </div>
</template>

<script>
// @ is an alias to /src
import NavBar from "@/components/NavBar.vue";
import UpperHeader from "@/components/UpperHeader.vue";
import HomePrincipal from "@/components/HomePrincipal.vue"
import HomeSecondary from "@/components/HomeSecondary.vue"
import MyFooter from "../components/MyFooter.vue"

export default {
  name: "Home",
  components: {
    UpperHeader,
    NavBar,
    HomePrincipal,
    HomeSecondary,
    MyFooter,
  },
};
</script>
<style>
.card-title{color: rgb(74, 75, 74);}
</style>