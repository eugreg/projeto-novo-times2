<script></script>

<template>
  <header>
    <span class="texto-header">Home</span>
    <span class="separador">|</span>
    <span class="texto-header">Jogadores</span>
    <span class="separador">|</span>
    <span class="texto-header">Times</span>
  </header>
  <main>Main</main>
  <footer>Rodapé</footer>
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

header,
footer {
  background-color: black;
  height: 10%;
  font-size: 1.3rem;
  color: white;
  display: flex;
  align-items: center;
  padding-left: 1.5rem;
}

header span {
  padding: 0 10px;
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
