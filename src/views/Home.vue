<template>
  <div class="home">
    <h1>MUTTER</h1>
    <img style="width: 350px" src="../assets/mutterlogo.png" />
    <HelloWorld msg="¡La aventura aguarda!" />
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
