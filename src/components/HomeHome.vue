<template>
<!-- navbar-dark -->
  <nav id="navbar" class="navbar custom-navbar navbar-expand-lg bg-body-tertiary fixed-top">
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-0 mb-lg-0 nav-pills">
        <li class="nav-item nav-link">
          <a class="nav-link active" aria-current="page" href="#home">Home</a>
        </li>
        <li class="nav-item nav-link flex-column">
          <a class="nav-link" aria-current="page" href="#about">About</a>
        </li>
        <li class="nav-item nav-link flex-column">
          <a class="nav-link" aria-current="page" href="#resume">Resume</a>
        </li>
        <li class="nav-item nav-link flex-column">
          <a class="nav-link" aria-current="page" href="#projects">Projects</a>
        </li>
      </ul>
    </div>
  </nav>
  <!--  -->
  <div id="home" class="home container-fluid" data-bs-target="#home">
    <div class="row">
      <div class="col pt-5 ps-5 text-start">
        <div class="row">
          <h1 class="text_name pt-10 fw-bold">MERLIN</h1>
          <h1 class="text_name fw-bold">BLICKISDORF</h1>
          <p class="text_student">
            Student in Electrical Engineering and Information Technology
          </p>
        </div>
        <div class="row pb-10">
          <div id="socials" class="socials col">
            <a
              class="link-underline-opacity-0 fs-1"
              style="color: black"
              href="https://linkedin.com/in/merlin-blickisdorf"
            >
              <i class="pe-3 bi bi-linkedin"></i>
            </a>
            <a
              class="ps-3 link-underline-opacity-0 fs-1"
              style="color: black"
              href="https://github.com/MBlick"
            >
              <i class="bi bi-github"></i>
            </a>
          </div>
        </div>
      </div>
      <!--  -->
      <div class="col-7 pt-5 d-flex justify-content-center align-items-center full-height text-start">
        <img
          class="image_circuit m-5 w-75"
          src="../assets/pseudo-circuit.png"
          alt="image of a pseudo circuit"
        />
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
.news {
  padding-top: 1%;
  padding-bottom: 1%;
}
.home {
  background-color: #52796f;
  align-content: center;
}
.text_name {
  font-size: 4rem;
}
.text_student {
  font-size: 2rem;
}
.navbar {
  padding-top: 0%;
  padding-bottom: 0%;
}
.custom-navbar {
  background-color: #252422 !important;
}
.nav-pills .nav-link.active {
  background-color: #eb5e28 !important;
  color: white !important;
}
.nav-pills .nav-link {
  color: white !important;
}
.nav-pills .nav-link:hover {
  color: #eb5e28 !important;
}
.pt-10 {
  padding-top: 15rem !important;
}
.pb-10 {
  padding-bottom: 15rem !important;
}
</style>
