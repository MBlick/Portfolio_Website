<template>
  <div id="about" class="about container-fluid">
    <div class="row">
      <div class="col">
        <h1 class="text-start">
          ABOUT
          </h1>
        <p class="text-start">
          I'm an electrical planner EFZ currently studiyng Electrical
          Engineering and Information Technology in my fifth semester at
          Lucerne University of Applied Sciences and Arts in Horw.
        </p>
      </div>
      <div class="col text-start">
        <p>test</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeAbout',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.about {
  background-color: aquamarine;
}

/* This sets the container height to the current display height */
.container-fluid {
  height: 100vh; 
}

</style>
