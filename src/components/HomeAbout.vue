<template>
  <div id="about" class="about container-fluid" data-bs-target="#about">
    <div class="row">
      <div class="col-7 p-5">
        <h1 class="text-start fw-bold">ABOUT</h1>
        <p class="text_about text-start">
          I'm an electrical planner EFZ currently studiyng Electrical
          Engineering and Information Technology in my fifth semester at
          Lucerne University of Applied Sciences and Arts in Horw.
        </p>
      </div>
      <div class="col">
        <img class="image_me" src="../assets/Image-of-myself.png" alt="image of myself">
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
  align-content: center;
}
/* This sets the container height to the current display height */
.container-fluid {
  height: 100vh; 
}
.text_about {
  font-size: 2em;
}
.image_me {
  max-width: 55%;
}


</style>
