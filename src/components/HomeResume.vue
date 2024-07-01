<template>
  <div id="resume" class="resume p-5 container-fluid" data-bs-target="#resume">
    <!-- Timeline 4 - Bootstrap Brain Component -->
    <section class="bsb-timeline-4 bg-light py-3 py-md-5 py-xl-8">
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-10 col-md-12 col-xl-10 col-xxl-9">
            <ul class="timeline">
              <li class="timeline-item left">
                <div class="timeline-body">
                  <div class="timeline-meta">
                  </div>
                  <div class="timeline-content timeline-indicator">
                    <div class="card border-0 shadow">
                      <div class="card-body p-xl-4">
                        <h2 class="card-title mb-2">Bootstrap 5</h2>
                        <h6 class="card-subtitle text-secondary mb-3">Active Support</h6>
                        <p class="card-text m-0">Powerful, extensible, and feature-packed frontend toolkit. Build and
                          customize with Sass, utilize prebuilt grid system and components, and bring projects to life
                          with powerful JavaScript plugins.</p>
                      </div>
                    </div>
                  </div>
                </div>
              </li>
              <li class="timeline-item right">
                <div class="timeline-body">
                  <div class="timeline-meta">
                  </div>
                  <div class="timeline-content timeline-indicator">
                    <div class="card border-0 shadow">
                      <div class="card-body p-xl-4">
                        <h2 class="card-title mb-2">Bootstrap 4</h2>
                        <h6 class="card-subtitle text-secondary mb-3">No Active Support</h6>
                        <p class="card-text m-0">Get started with Bootstrap, the world’s most popular framework for
                          building responsive, mobile-first sites, with jsDelivr and a template starter page. Bootstrap 4
                          has no active support.</p>
                      </div>
                    </div>
                  </div>
                </div>
              </li>
              <li class="timeline-item left">
                <div class="timeline-body">
                  <div class="timeline-meta">
                  </div>
                  <div class="timeline-content timeline-indicator">
                    <div class="card border-0 shadow">
                      <div class="card-body p-xl-4">
                        <h2 class="card-title mb-2">Bootstrap 3</h2>
                        <h6 class="card-subtitle text-secondary mb-3">No Active Support</h6>
                        <p class="card-text m-0">Bootstrap is the most popular HTML, CSS, and JS framework for developing
                          responsive, mobile first projects on the web. Bootstrap 3 has no active support.</p>
                      </div>
                    </div>
                  </div>
                </div>
              </li>
              <li class="timeline-item right">
                <div class="timeline-body">
                  <div class="timeline-meta">
                  </div>
                  <div class="timeline-content timeline-indicator">
                    <div class="card border-0 shadow">
                      <div class="card-body p-xl-4">
                        <h2 class="card-title mb-2">Bootstrap 2</h2>
                        <h6 class="card-subtitle text-secondary mb-3">No Active Support</h6>
                        <p class="card-text m-0">Sleek, intuitive, and powerful front-end framework for faster and easier
                          web development. Bootstrap 2 is no longer officially supported.</p>
                      </div>
                    </div>
                  </div>
                </div>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </section>
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
@import "https://unpkg.com/bootstrap@5.3.3/dist/css/bootstrap.min.css";
@import "https://unpkg.com/bs-brain@2.0.4/tutorials/timelines/timeline-4/assets/css/timeline-4.css";

.resume {
  background-color: #52796f;
}
.bg-light {
  background-color: #52796f !important;
}
.p-10 {
  padding: 7rem !important;
  /* 112px */
}</style>
