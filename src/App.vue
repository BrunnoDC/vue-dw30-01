<script setup>
import HeaderComp from "@/components/template/HeaderComp.vue";
import RodapeComp from "./components/template/RodapeComp.vue";
</script>

<template>
  <HeaderComp />
  <RouterView />
  <RodapeComp />
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
</style>
