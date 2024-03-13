<template>
<nav id="navbar" class="navbar navbar-expand-lg bg-body-tertiary">
    <div class="">
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#home">Home</a>
        </li>

        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#about">About</a>
        </li>

        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#resume">Resume</a>
        </li>

        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#projects">Projects</a>
        </li>
      </div>
    </div>
  </nav>
  <div id="home" class="home container-fluid">
    <div class="row">
      <div class="col text-start">
        <h1>
          MERLIN VALENTIN
        </h1>
        <h1>
          BLICKISDORF
        </h1>
        <p>Student in Electrical Engineering</p>
        <div class="row">
          <div class="col">
            <a class="link-underline-opacity-0 fs-1" style="color: #f67280;" href="https://linkedin.com/in/merlin-blickisdorf">
            <i class="bi bi-linkedin"></i>
            </a>
          </div>
          <div class="col">
            <a class="link-underline-opacity-0 fs-1" style="color: #f67280;" href="https://github.com/MBlick">
            <i class="bi bi-github"></i>
            </a>
          </div>
        </div>
      </div>
      <div class="col text-start">
        <p>some picture or canvas of a circuit</p>
        <p>???scrolling with scrollspy, for the snapping effect???</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeAboutMe',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.news {
  padding-top: 1%;
  padding-bottom: 1%;
  background-color: white;
}

h3 {
  margin: 40px 0 0;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}

.home {
  background-color: blueviolet;
}

/* This sets the container height to the current display height */
.container-fluid {
  height: 100vh; 
}

</style>
