<template>
  <!-- Navbar -->
  <nav id="navbar" class="navbar custom-navbar navbar-expand-lg bg-body-tertiary fixed-top">
    <div class="container-fluid">
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-0 mb-lg-0 nav-pills">
          <li class="nav-item nav-link">
            <a class="nav-link active" aria-current="page" href="#home" @click="closeNavbar">Home</a>
          </li>
          <li class="nav-item nav-link flex-column">
            <a class="nav-link" aria-current="page" href="#about" @click="closeNavbar">About</a>
          </li>
          <li class="nav-item nav-link flex-column">
            <a class="nav-link" aria-current="page" href="#resume" @click="closeNavbar">Resume</a>
          </li>
          <li class="nav-item nav-link flex-column">
            <a class="nav-link" aria-current="page" href="#projects" @click="closeNavbar">Projects</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <!-- Home Section -->
  <div id="home" class="home container-fluid full-height" data-bs-target="#home">
    <div class="row align-items-center justify-content-center">
      <div class="col pt-3 pt-lg-5 ps-3 ps-lg-5 text-start">
        <div class="row">
          <h1 class="text_name pt-10 fw-bold">MERLIN</h1>
          <h1 class="text_name fw-bold">BLICKISDORF</h1>
          <p class="text_student">
            Bachelor in Electrical Engineering and Information Technology
          </p>
        </div>
        <div class="row">
          <div id="socials" class="socials col">
            <a class="link-underline-opacity-0 fs-1" style="color: black"
              href="https://linkedin.com/in/merlin-blickisdorf" target="_blank">
              <i class="pe-3 bi bi-linkedin"></i>
            </a>
            <a class="ps-3 link-underline-opacity-0 fs-1" style="color: black" href="https://github.com/MBlick"
              target="_blank">
              <i class="bi bi-github"></i>
            </a>
          </div>
        </div>
      </div>
      <!--  -->
      <div class="col-7 pt-3 pt-lg-5 d-flex justify-content-center align-items-center">
        <img class="image_circuit p-3 p-lg-5 w-custom" src="../assets/pseudo-circuit.png"
          alt="image of a pseudo circuit" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HomeAboutMe",
  methods: {
    closeNavbar() {
      const navbarToggler = document.querySelector('.navbar-toggler');
      const navbarCollapse = document.querySelector('#navbarSupportedContent');

      if (navbarCollapse.classList.contains('show')) {
        navbarToggler.click();
      }
    },
  },
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

.full-height {
  height: 100vh;
}

.home {
  background-color: #52796f;
  align-content: center;
}

.text_name {
  font-size: 4rem;
  word-wrap: break-word;
}

.text_student {
  font-size: 2rem;
}

.w-custom {
  width: 85%;
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

.navbar-toggler {
  background-color: #eb5e28 !important;
  border-color: #eb5e28 !important;
}

/* Media query for smartphones (up to 768px wide) */
@media (max-width: 850px) {
  .full-height {
    height: 100vh;
  }

  .text-start {
    text-align: center;
  }

  .text_name {
    text-align: center;
    font-size: 3rem;
  }

  .text_student {
    text-align: center;
    font-size: 1.8rem;
  }

  .socials {
    justify-content: center;
    text-align: center;
  }

  .fs-1 {
    font-size: 2.5rem !important;
    /* Increase the font size of social icons */
  }

  body {
    overflow-x: hidden;
    /* Prevent horizontal overflow on small screens */
  }

  .image_circuit {
    display: none;
  }
}

/* Media query for extra large screens (2000px and up) */
@media (min-width: 2000px) {
  .image_circuit {
    max-width: 70%;
  }
}

@media (height <= 600px) {
  .image_circuit {
    display: none;
  }
}
</style>
