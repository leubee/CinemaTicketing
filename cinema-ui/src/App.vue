<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <ElementUIComponentSet></ElementUIComponentSet>
    <AsyncProgrammingTemplate />
  </div>
</template>

<script>
import ElementUIComponentSet from "@/components/ElementUIComponentSet";
import AsyncProgrammingTemplate from "@/components/AsyncProgrammingTemplate";

export default {
  name: 'App',
  components: {
    AsyncProgrammingTemplate,
    ElementUIComponentSet
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
