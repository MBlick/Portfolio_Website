<template>
  <div id="projects" class="projects p-5 container-fluid" data-bs-target="#projects">
    <div class="row pt-4">
      <div class="col text-start">
        <h1>JOB</h1>
        <h3>Electrical Planning:</h3>
        <p></p>
        <h3>Fiber to the Street:</h3>
        <p></p>
        <h3>Mobile Antennas:</h3>
        <p></p>
      </div>
      <div class="col text-start">
        <h1>UNIVERSITY</h1>
        <p class="ps-4">AE (Advanced Electronics) - Rogowski Coil</p>
        <p class="ps-4">ELO2 (Electronics 2) - Smoke Detector</p>
        <p class="ps-4">PREN1 & PREN2 (Project Unit) - Gravel Cleaner Robot</p>
      </div>
      <div class="col text-start">
        <h1>PRIVATE</h1>
        <p class="ps-4">This Portfolio Website</p>
        <p class="ps-4">Lab Powersupply V2</p>
        <p class="ps-4">Portable Ventilator</p>
        <p class="ps-4">Desk-PC</p>
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
