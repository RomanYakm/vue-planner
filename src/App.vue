<template>
  <Navbar />
  <router-view />
</template>

<script>
import Navbar from "./components/NavbarItem.vue";

export default {
  components: { Navbar },
};
</script>

<style lang="scss">
body {
  background: #f2f2f2;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  max-width: 600px;
  margin: 0 auto;
  color: #555;
}
</style>
