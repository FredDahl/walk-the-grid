<template>
  <div class="home-container">
    <!-- <img alt="Vue logo" src="../assets/logo.png" /> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    <div class="home-component-container"><FinalPosition /></div>
    <div class="home-component-container"><CalcFirstIntersection /></div>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import FinalPosition from "@/components/FinalPosition.vue";
import CalcFirstIntersection from "@/components/CalcFirstIntersection.vue";

export default {
  name: "Home",
  components: {
    FinalPosition,
    CalcFirstIntersection,
  },
};
</script>

<style scoped>
.home-container {
  height: 100vh;
  background-color: #ebebeb;
}
.home-component-container {
  padding: 50px;
}
</style>