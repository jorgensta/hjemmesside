<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <div class="circleContainer">
      <circle-component></circle-component>
    </div>
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import CircleComponent from "@/components/CircleComponent.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
    CircleComponent
  }
};
</script>

<style lang="sass">
.circleContainer
  margin-left: 600px
</style>
