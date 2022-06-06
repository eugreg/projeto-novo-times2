<script setup>
import HeaderComp from "./components/template/HeaderComp.vue";
import FoterComp from "./components/template/FoterComp.vue";
</script>

<template>
  <HeaderComp />
  <main>
  <RouterView />
  </main>
  <FoterComp />
</template>

<style>
@import "@/assets/base.css";

#app {
  /* max-width: 1280px; */
  margin: 0 auto;
  /* padding: 2 rem; */
  height: 100vh;

  font-weight: normal;
}
a {
  color: inherit;
  text-decoration: none;
}
a:hover {
  border: solid #000000 0.5px;
}



main {
  min-height: 80%;
}

/*.conteudo {
  border: 1px solid black;
  width: 100px;
  height: 50px;
  overflow: scroll;
}*/
</style>
