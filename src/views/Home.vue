<template>
  <div class="home">
    <header>
      <UpperHeader />
    </header>
    <NavBar />
    <main>
      <h1>Meet our family</h1>
      <h2> and join us</h2>
      <div class="content">
        <HomePrincipal />
        <MoreInfo />
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
import MoreInfo from "@/components/MoreInfo.vue"
import MyFooter from "@/components/MyFooter.vue"


export default {
  name: "Home",
  components: {
    UpperHeader,
    NavBar,
    HomePrincipal,
    MyFooter,
    MoreInfo
  },
};
</script>
<style>
.card-title {
  color: rgb(74, 75, 74);
}
h1 {
  padding-top: 25px;
}
</style>