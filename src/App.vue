<template>
  <div data-bs-spy="scroll">
    <HomeHome />
    <HomeAbout />
    <HomeResume />
    <HomeProjects />
    <HomeFooter />
  </div>
</template>

<script>
import HomeHome from './components/HomeHome.vue'
import HomeAbout from './components/HomeAbout.vue'
import HomeResume from './components/HomeResume.vue'
import HomeProjects from './components/HomeProjects.vue'
import HomeFooter from './components/HomeFooter.vue'

export default {
  name: 'App',
  components: {
    HomeHome,
    HomeAbout,
    HomeResume,
    HomeProjects,
    HomeFooter,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: black;
}

html, body {
  overflow-x: hidden;
}
</style>
