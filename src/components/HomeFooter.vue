<template>
  <!-- Footer Section -->
  <div id="footer" class="footer container-fluid">
    <div class="pt-3">
      <p class="text_footer mx-auto">Copyright © <span id="year"></span> Merlin Blickisdorf. All rights reserved.</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "HomeFooter",
  props: {
    msg: String,
  },
};
document.addEventListener("DOMContentLoaded", function () {
  document.getElementById('year').textContent = new Date().getFullYear();
});
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.footer {
  background-color: #252422;
  align-content: center;
  color: white;
}

/* Media query for smartphones (up to 768px wide) */
@media (max-width: 768px) {

  body {
    overflow-x: hidden;
    /* Prevent horizontal overflow on small screens */
  }
}
</style>
