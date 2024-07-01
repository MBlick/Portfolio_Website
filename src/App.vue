<template>
  <div data-bs-spy="scroll">
    <HomeHome />
    <HomeAbout />
    <HomeResume />
    <HomeProjects />
  </div>
</template>

<script>
import HomeHome from './components/HomeHome.vue'
import HomeAbout from './components/HomeAbout.vue'
import HomeResume from './components/HomeResume.vue'
import HomeProjects from './components/HomeProjects.vue'

export default {
  name: 'App',
  components: {
    HomeHome,
    HomeAbout,
    HomeResume,
    HomeProjects,
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
</style>
