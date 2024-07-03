<template>
  <!-- About Section -->
  <div id="about" class="about container-fluid full-height" data-bs-target="#about">
    <div class="row">
      <div class="col-sm pt-10 ps-3 ps-lg-5 pe-3 pe-lg-5 pe-lg-0">
        <h1 class="text-start fw-bold">ABOUT</h1>
        <p class="text_about text-start pb-10">
          I'm an electrical planner EFZ currently studiyng Electrical
          Engineering and Information Technology in my seventh semester at Lucerne
          University of Applied Sciences and Arts in Horw.
        </p>
      </div>
      <!--  -->
      <div class="col-sm d-flex justify-content-center align-items-center">
        <img class="image_me m-5 w-100" src="../assets/image-of-myself.png" alt="image of myself" />
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
.full-height {
  height: 100vh;
}
.text-start {
  font-size: 3rem;
}
.text_about {
  font-size: 2em;
}
.image_me {
  max-width: 55%;
}
.pt-10 {
  padding-top: 20rem !important;
}
.pb-10 {
  padding-bottom: 20rem !important;
}

/* Media query for smartphones (up to 768px wide) */
@media (max-width: 768px) {
  .full-height {
    height: auto;
  }
  .text-start {
    text-align: center !important;
  }
  .pt-10 {
    padding-top: 4rem !important;
  }
  .pb-10 {
    padding-bottom: 3rem !important;
  }
  .text_about {
    padding-bottom: 0rem;
  }
  .image_me {
    padding-bottom: 6rem;
  }
  body {
    overflow-x: hidden;
    /* Prevent horizontal overflow on small screens */
  }
}
</style>
