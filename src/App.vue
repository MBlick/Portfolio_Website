<template>
  <div class="margin">
    <HomeNavbar />
    <HomeHome />
    <HomeAboutMe />
    <HomeProjects />
    <HomeContact />
    <HomeFooter />
  </div>
</template>

<script>
import HomeNavbar from './components/HomeNavbar.vue'
import HomeHome from './components/HomeHome.vue'
import HomeAboutMe from './components/HomeAboutMe.vue'
import HomeProjects from './components/HomeProjects.vue'
import HomeContact from './components/HomeContact.vue'
import HomeFooter from './components/HomeFooter.vue'

export default {
  name: 'App',
  components: {
    HomeNavbar,
    HomeHome,
    HomeAboutMe,
    HomeProjects,
    HomeContact,
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
  color: #2c3e50;
  background-image: url("assets/pexels.jpg");
}

.margin {
  margin-left: 5%;
  margin-right: 5%;
}
</style>
