<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
// import data from "../../mock/data.json";
export default {
  name: "HomeView",
  components: {
    HelloWorld,
  },
  mounted() {
    // console.log(data, "data");
    const data = require("../../mock/data.json");
    console.log(data, "data");
  },
};
</script>
