<template>
  <div class="container-fluid mt-3">
    <div class="jumbotron">
      <h1>Bienvenidos al TP4 de la materia PNT2</h1>
      <Navbar />
      <router-view></router-view>
    </div>
  </div>
</template>

<script>
import Navbar from "./componentes/Navbar.vue";

export default {
  name: "App",
  components: {
    Navbar,
  },
};
</script>

<style>
</style>
