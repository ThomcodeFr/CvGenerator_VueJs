<template>
  <div id="app">
    <div class="background">
      <Presentation />
      <Trombi />
      <Localisation />
    </div>
  </div>
</template>

<script>
import Presentation from '../components/about/Presentation'
import Trombi from '../components/about/Trombi'
import  Localisation from '../components/about/Localisation'

export default {
  name: 'App',
  components: {
    Presentation,
    Trombi,
    Localisation
  },
}
</script>

<style></style>
