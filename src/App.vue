<template>
  <div id="app">
    <Header/>
    <!-- <img alt="Vue logo" src="./assets/vueflix.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
import Header from "./components/Header.vue"

export default {
  name: 'App',
  components: {
    // HelloWorld
    Header,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  margin: 0;
  padding: 0;
}
.vueflix-btn{
  background: #e50914;
  border: 1px solid #e50914;
  text-transform: capitalize;
  padding: 8px 16px;
  border-radius: 4px;
  font-weight: 400;
  margin: 1rem auto;
  cursor: pointer;

}
</style>
