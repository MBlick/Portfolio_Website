<template>
  <div id="about" class="about container-fluid" data-bs-target="#about">
    <div class="row">
      <div class="col-7 pt-10 ps-5">
        <h1 class="text-start fw-bold">ABOUT</h1>
        <p class="text_about text-start pb-10">
          I'm an electrical planner EFZ currently studiyng Electrical
          Engineering and Information Technology in my seventh semester at Lucerne
          University of Applied Sciences and Arts in Horw.
        </p>
      </div>
      <!--  -->
      <div class="col d-flex justify-content-center align-items-center full-height">
        <img
          class="image_me w-100"
          src="../assets/Image-of-myself.png"
          alt="image of myself"
        />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HomeAbout",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.about {
  background-color: #354f52;
  align-content: center;
}
/* This sets the container height to the current display height */
.text_about {
  font-size: 2em;
}
.image_me {
  max-width: 55%;
}
.pt-10 {
  padding-top: 10rem !important; /* 112px */
}
.pb-10 {
  padding-bottom: 10rem !important; /* 112px */
}
</style>
