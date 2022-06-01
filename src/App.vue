<template>
<header class="menu-superior" >
    <div class="menu-esquerdo" >
    <span> Home </span>
    <span>|</span>
    <span> Times </span>
    <span>|</span>
    <span>Jogadores</span>
    </div>
    <div class="menu-direito" >
    <span>Sair</span>
    </div>
  </header>
<RouterView/>
</template>

<style>
@import "@/assets/base.css";

#app {
  max-width: 1280px;
  margin: 0 auto;
  /*padding: 2rem;*/
  height: 100vh;

  font-weight: normal;
}
header {
  background-color: lightblue;
  color: blue;
  height: 10%;
  font-size: 1.3rem;
  display: flex;
}
footer {
  background-color: lightblue;
  color: blue;
  height: 10%;
  font-size: 1.3rem;
}
main {
  height: 80%;
  background-color: lightskyblue;
  color: white;
}

header.menu-superior {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
header span {
  padding: 0 20px;
}
</style>
