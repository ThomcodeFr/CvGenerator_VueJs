<template>
  <div id="app">
    <img id="home-logo" src= "@/assets/logo-blue.png" alt="Logo des 8 fantastiques"/>
    <Header />
    <Content />
    <Footer />
  </div>

</template>

<script>
import Header from './components/Header'
import Content from './components/HomeContent'
import Footer from './components/HomeFooter'


export default {
  name: 'App',
  components: {
    Header,
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
