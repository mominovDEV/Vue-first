<template>
<div>
  <div>
    <Navbar/>
  </div>

  <div>
    <Header/>
  </div>

  <div class="page2">
    <Page2/>
  </div>

  <div>
    <Page3/>
  </div>
  <div>
    <Projects/>
  </div>
  <div>
    <team/>
  </div>

</div>
</template>
<script setup>
import Navbar from './components/Navbar'
import Header from './components/header.vue'
import Page2 from './components/page2.vue'
import Page3 from './components/page3.vue'
import Projects from './components/projects.vue'
import team from './components/TeamComponent'

</script>
<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}


</style>
