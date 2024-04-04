<template>
  <div id="resume" class="resume p-5 container-fluid" data-bs-target="#resume">
    <div class="row text-start pt-5 h-50">
      <div class="technology col-3">
        <h1 class="fw-bold">TECHNOLOGY</h1>
        <p class="ps-4">
          Programming: C, C#, Assembler, Python, Linux, HTML, CSS, PHP
        </p>
        <p class="ps-4">Software: Tina, Altium, Siemens NX, MATLAB</p>
        <p class="ps-4">whatnot???:</p>
      </div>
      <!--  -->
      <div class="education col-6">
        <h1 class="fw-bold">EDUCATION</h1>
        <p class="ps-4">Sep 2021 - Jul 2025: Bachelor (FH) EEIT, HSLU, Horw</p>
        <p class="ps-4">
          Aug 2020 - Jul 2021: Vocational Baccalaurete, BBZB, Lucerne
        </p>
        <p class="ps-4">
          Aug 2014 - Jul 2018: Apprenticeship, Electrical Planner EFZ, Network
          41, Sursee
        </p>
      </div>
      <!--  -->
      <div class="interests col-3">
        <h1 class="fw-bold">INTERESTS</h1>
        <p class="ps-4">DIY Projects</p>
        <p class="ps-4">Automation</p>
        <p class="ps-4">3D Printing</p>
        <p class="ps-4">Repair of electrical devices</p>
        <p class="ps-5">Voluntary Work @ Repair Café Luzern</p>
      </div>
    </div>
    <!--  -->
    <div class="row text-start pt-5 h-50">
      <div class="language col-3">
        <h1 class="fw-bold">LANGUAGE</h1>
        <p class="ps-4">German (native)</p>
        <p class="ps-4">English (fluent, C1 level)</p>
        <p class="ps-4">French (basic)</p>
      </div>
      <!--  -->
      <div class="experience col-6">
        <h1 class="fw-bold">EXPERIENCE</h1>
        <p class="ps-4">
          Aug 2022 - Sep 2023: Electrical Planner EFZ, HT Infraserv AG,
          Entlebuch, 20% pensum
        </p>
        <p class="ps-4">
          Nov 2020 - Jul 2021: Student Help, TopShop AG, Rothenburg, 20% pensum
        </p>
        <p class="ps-4">
          Jul 2018 - Jul 2020: Electrical Planner EFZ, Network 41 AG, Sursee
        </p>
      </div>
      <!--  -->
      <div class="hobbies col-3">
        <h1 class="fw-bold">HOBBIES</h1>
        <p class="ps-4">Skiing</p>
        <p class="ps-4">Squash</p>
        <p class="ps-4">Fitness</p>
        <p class="ps-4">Chess</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HomeAboutMe",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.resume {
  background-color: #52796f;
}
/* This sets the container height to the current display height */
.container-fluid {
  height: 100vh;
}
</style>
