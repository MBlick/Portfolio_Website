<template>
  <div id="projects" class="projects container-fluid">
    <div class="row">
      <div class="col text-start">
        <p>test</p>
      </div>
      <div class="col text-start">
        <p>test</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeProjects',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.projects {
  background-color: aqua;
}

/* This sets the container height to the current display height */
.container-fluid {
  height: 100vh; 
}

</style>
