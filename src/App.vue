<template>
  <div id="app">
    <Header />
    <img alt="Vue logo" src="./assets/logo.png" />
    <MainPage msg="Welcome to Your Vue.js App" />
    <Footer />
  </div>
</template>

<script>
import MainPage from './components/MainPage.vue'
import Header from './components/Header.vue'

export default {
  name: 'App',
  components: {
    MainPage,
    Header,
  },
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
