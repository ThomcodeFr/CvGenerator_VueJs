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
/* import Content from './components/Content' */
import Content from './pages/About'
import Footer from './components/Footer'


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


h1 {
    color: rgb(193, 162, 109);
}

h2{
    color: rgb(193, 162, 109);
}

.background {
  background: url('./assets/network.jpg');
  height: auto;
}

@media screen and (max-width: 640px) {
  #team-infos {
    display: flex;
    flex-direction: column;
  }

  h1 {
    text-align: center;
  }

  .title-font {
    color: rgb(193, 162, 109);
    text-align: center;
    font-size: 30px;
  }

  #team img {
    height: 60px;
    width: 60px;
    border-radius: 90%;
    border: 3px solid rgb(193, 162, 109);
    filter: grayscale(1);
  }

  #team img:hover {
    filter: grayscale(0);
  }

  .presentation {
    margin: 0;
  }

  .presentation p {
    margin: 0 2%;
  }

  #localisation {
    display: flex;
    flex-direction: column;
    padding-bottom: 30px;
  }

  #adress {
    margin: auto;
    padding-bottom: 10px;
  }

  .map-configuration {
    width: auto;
    height: auto;
  }
}
</style>
