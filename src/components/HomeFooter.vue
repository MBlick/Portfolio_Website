<template>
  <div id="footer" class="footer">
    <footer class="d-flex flex-wrap justify-content-between">
      <div class="mx-auto p-2 m-2">
        <a class="link-opacity-25 fs-1 m-4" href="https://www.linkedin.com/in/merlin-blickisdorf/">
          <i class="bi bi-linkedin"></i>
        </a>
        <a class="link-opacity-25 fs-1 m-4" href="https://github.com/MBlick">
          <i class="bi bi-github"></i>
        </a>
        <p class="fs-4 m-0">Made with love by Merlin Blickisdorf</p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'HomeFooter',
  props: {
    msg: String
  }
}
</script>

<style scoped>
.footer {
  padding-top: 1%;
  background-color: gray;
}
.bi {
  color: orange;
}
</style>
