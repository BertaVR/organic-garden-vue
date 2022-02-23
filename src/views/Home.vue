<template>

  <div class="home">
    <UpperHeader></UpperHeader>
    <NavBar/>
    

  </div>
</template>

<script>
// @ is an alias to /src
import NavBar from "@/components/NavBar.vue";
import UpperHeader from "../components/UpperHeader.vue";

export default {
  name: "Home",
  components: {
    UpperHeader,
    NavBar
},
};
</script>
