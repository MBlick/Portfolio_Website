<template>
  <nav id="navbar" class="navbar bg-dark navbar-expand-lg bg-body-tertiary fixed-top" data-bs-theme="dark">
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-0 mb-lg-0 nav-pills">
        <li class="nav-item nav-link">
          <a class="nav-link active" aria-current="page" href="#home">Home</a>
        </li>
        <li class="nav-item nav-link flex-column">
          <a class="nav-link" aria-current="page" href="#about">About</a>
        </li>
        <li class="nav-item nav-link flex-column">
          <a class="nav-link" aria-current="page" href="#projects">Projects</a>
        </li>
        <li class="nav-item nav-link flex-column">
          <a class="nav-link" aria-current="page" href="#resume">Resume</a>
        </li>
      </ul>
    </div>
  </nav>

  <div id="home" class="home container-fluid" data-bs-target="#home">
    <div class="row">
      <div class="col p-5 text-start">
        <div class="row">
          <h1 class="text_name fw-bold">MERLIN</h1>
          <h1 class="text_name fw-bold">BLICKISDORF</h1>
          <p class="text_student">Student in Electrical Engineering and Information Technology</p>
        </div>
        <div class="row">
          <div id="socials" class="socials col">
            <a class="link-underline-opacity-0 fs-1" style="color: black" href="https://linkedin.com/in/merlin-blickisdorf">
            <i class="pe-3 bi bi-linkedin"></i>
            </a>
            <a class="ps-3 link-underline-opacity-0 fs-1" style="color: black" href="https://github.com/MBlick">
            <i class="bi bi-github"></i>
            </a>
          </div>
        </div>
      </div>

      <div class="col-7 p-5 text-start">
        <p>some picture or canvas of an electrical circuit</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeAboutMe',
  props: {
    msg: String
  },
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.news {
  padding-top: 1%;
  padding-bottom: 1%;
  background-color: white;
}
.home {
  background-color: blueviolet;
  align-content: center;
}
.text_name {
  font-size: 4rem;
}
.text_student {
  font-size: 2rem;
}
/* This sets the container height to the current display height */
.container-fluid {
  height: 100vh; 
}
</style>
