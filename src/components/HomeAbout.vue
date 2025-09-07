<template>
  <!-- About Section -->
  <div id="about" class="about container-fluid full-height" data-bs-target="#about">
    <div class="row align-items-center justify-content-center">
      <div class="col-sm ps-3 ps-lg-5 pe-3 pe-lg-5 pe-lg-0">
        <h1 class="title_about text-start fw-bold">ABOUT</h1>
        <p class="text_about text-start pb-10">
          Hi, I'm Merlin, a recent graduate in Electrical Engineering and Information Technology 
          from the Lucerne University of Applied Sciences and Arts 
          in Horw, where I also contributed to the AMZ-Racing project of 2025 for my bachelor's thesis.
        </p>
        <p class="text_about text-start pb-10">
          This portfolio is a showcase of my journey as an engineer,
          from my studies to my bachelor's thesis at AMZ Racing and beyond. 
          Here, you'll find a timeline of my academic and professional milestones, 
          with a strong focus on the projects that shaped my skills and passion for engineering.
        </p>
      </div>
      <!--  -->
      <div class="p-lg-5 col-sm d-flex justify-content-center align-items-center">
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
  font-size: 1.8em;
}

.image_me {
  max-width: 55%;
}

/* Media query for smartphones (up to 768px wide) */
@media (max-width: 768px) {
  .full-height {
    height: auto;
  }

  .title_about {
    padding-top: 4rem;
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

/* Media query for extra large screens (2000px and up) */
@media (min-width: 2000px) {
  .image_me {
    max-width: 35%;
  }
}
</style>
