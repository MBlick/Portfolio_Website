<template>
  <nav id="navbar" class="navbar navbar-expand-lg bg-body-tertiary">
    <div class="container-fluid">
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <a class="navbar-brand" href="#home">Merlin Blickisdorf</a>

        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#home">Home</a>
        </li>

        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#aboutme">About Me</a>
        </li>

        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#projects">Projects</a>
        </li>

        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#contact">Contact</a>
        </li>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'HomeNavbar',
  props: {
    msg: String
  }
}
</script>

<style scoped>
.navbar {
  padding-top: 1%;
  padding-bottom: 1%;
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
</style>
