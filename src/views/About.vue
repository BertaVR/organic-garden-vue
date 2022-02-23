<template>
  <div class="about">
    <UpperHeader></UpperHeader>
    <navBar></navBar>
    <h1>This is an about page</h1>
  </div>
</template>
<script>

import NavBar from "@/components/NavBar.vue";
import UpperHeader from "../components/UpperHeader.vue";

export default {
  name: "About",
  components: {
    NavBar,
    UpperHeader
},
};
</script>