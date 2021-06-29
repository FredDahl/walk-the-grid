<template>
  <div class="home-container">
    <div class="home-component-container"><FinalPosition /></div>
    <div class="home-component-container"><CalcFirstIntersection /></div>
  </div>
</template>

<script>
// @ is an alias to /src
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