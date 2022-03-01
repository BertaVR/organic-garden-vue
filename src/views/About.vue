<template>
  <div class="about">
    <main>
      <header>
        <UpperHeader />
      </header>
      <navBar />
      <h1>About</h1>
      <h2>Who are we?</h2>
      <AboutPage></AboutPage>
      <MoreInfo />
    </main>
    <MyFooter />
  </div>
</template>
<script>

import NavBar from "@/components/NavBar.vue";
import UpperHeader from "@/components/UpperHeader.vue";
import AboutPage from "@/components/AboutPage.vue"
import MyFooter from "@/components/MyFooter.vue";
import MoreInfo from "@/components/MoreInfo.vue";


export default {
  name: "About",
  components: {
    NavBar,
    UpperHeader,
    AboutPage,
    MyFooter,
    MoreInfo
  },
};
</script>