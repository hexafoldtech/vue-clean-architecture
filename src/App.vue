<template>
  <LoginPage></LoginPage>
  <Footer msg="Welcome to Your Vue.js App"/>
</template>

<script>
import Footer from './presentation/components/Footer.vue'
import LoginPage from './presentation/pages/Login.vue'

export default {
  name: 'App',
  components: {
    Footer,
    LoginPage
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
