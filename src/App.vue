<template>
  <div id="app">
    <img id="home-logo" src= "@/assets/logo-blue.png" alt="Logo des 8 fantastiques"/>
    <Home />
    <Content />
    <Footer />


  </div>

</template>

<script>
import Home from './components/Home'
import Content from './components/HomeContent'
import Footer from './components/HomeFooter'


export default {
  name: 'App',
  components: {
    Home,
    Content,
    Footer,
  },
}
</script>

<style>
#app {
  font-family: "Oswald", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

#home-logo {
  position : relative;
  width: 150px;
}
</style>
