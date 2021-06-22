<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png" /> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    <ExamplePosition />
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
import ExamplePosition from "@/components/ExamplePosition.vue";

export default {
  name: "Home",
  components: {
    ExamplePosition,
  },
};
</script>
