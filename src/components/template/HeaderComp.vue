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
</template>
<style>
header span {
  padding: 0 10px;
}
header {
  background-color: black;
  height: 10%;
  font-size: 1.3rem;
  color: white;
  display: flex;
  align-items: center;
  padding-left: 1.5rem;
  justify-content: space-between;
}
</style>
