<script></script>

<template>
  <header>
    <div class="menu-esquerdo">
      <span><RouterLink to="/">Home</RouterLink></span>
      <span>|</span>
      <span><RouterLink to="/times">Times</RouterLink></span>
      <span>|</span>
      <span><RouterLink to="/jogadores">Jogadores</RouterLink></span>
    </div>
    <div class="menu-dieito">
      <span>Sair</span>
    </div>
  </header>
  <RouterView />
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
  justify-content: space-between;
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
