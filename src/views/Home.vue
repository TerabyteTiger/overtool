<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <p>
      The overuse and overpromotion of React (sledgehammer to crack a nut in
      most cases)
    </p>
    <p>
      The ridiculous amount of tooling people seem to think is necessary to
      build a simple website
    </p>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
  },
};
</script>
