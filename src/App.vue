<template>
  <div id="app">
    <div id="nav">

<div class="nombre">
  <router-link to="/" class="no"> Luis Angel Mendoza Chate</router-link>
</div>

      <div class="contenido">
      <router-link to="/" class="direccon">Projects</router-link> 
      <router-link to="/about" class="direccon">About</router-link> 
      <router-link to="/yo" class="direccon">Contact</router-link>
      <!--<a href="https://api.whatsapp.com/send?phone=51902013952&text=holasas" target="_blank"> Hola</a>-->
      </div>
    </div>
    <router-view />
  </div>
</template>

<script>
export default {
  name: "orange-page",
  created: function () {
    //document.body.style.backgroundColor = "black";
  },
  destroyed: function () {
    document.body.style.backgroundColor = null;
  },
};
</script>


<style lang="scss" src="../src/assets/css/header.scss" scoped>
</style>
