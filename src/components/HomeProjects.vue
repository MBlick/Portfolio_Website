<template>
  <div
    id="projects"
    class="projects p-5 container-fluid"
    data-bs-target="#projects"
  >
    <div class="row pt-5">
      <div class="col">
        <h1 class="pb-3 fw-bold">JOB</h1>
        <div class="accordion" id="accordionJob">
          <div class="accordion-item">
            <h2 class="accordion-header" id="headingELP">
              <button
                class="accordion-button"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#collapseELP"
                aria-expanded="true"
                aria-controls="collapseELP"
              >
                <strong>Electrical Planning</strong>
              </button>
            </h2>
            <div
              id="collapseELP"
              class="accordion-collapse collapse show"
              aria-labelledby="headingELP"
              data-bs-parent="#accordionJob"
            >
              <div class="accordion-body text-start">
                <p class="justified-text">
                  As an electrical planner, my job was it to create electrical
                  plans, schemes and tenders for the electricians on the
                  construction site. In my two-year period after the
                  apprenticeship at Network 41 AG and in the summer jobs at
                  HT-Infraserv AG I've worked on several interesting projects. A
                  few can be seen in the following list:
                </p>
                <a
                  href="https://www.google.ch/maps/place/Hochstrasser+AG+Kaffeer%C3%B6sterei/@47.0488536,8.2694026,106m/data=!3m1!1e3!4m6!3m5!1s0x478ffb3911826457:0x91fc009c32b76518!8m2!3d47.0489444!4d8.2696281!16s%2Fg%2F1td1259t?entry=ttu"
                  target="_blank"
                  >Hochstrasser AG - New coffee roastery in Lucerne</a
                ><br />
                <a
                  href="https://www.google.ch/maps/place/Aarau/@47.3911964,8.0503103,248m/data=!3m1!1e3!4m6!3m5!1s0x47903bf01e450701:0x1f73bd9ca50dce70!8m2!3d47.3913661!4d8.0512862!16s%2Fm%2F0r3t4xh?entry=ttu"
                  target="_blank"
                  >Aarau railroad station - Renewal of the lighting</a
                ><br />
                <a
                  href="https://www.hp-arch.ch/werkverzeichnis?c=Neubau_Doppelturnhalle_in_Schenkon"
                  target="_blank"
                  >Village of Schenkon - New double sports hall</a
                ><br />
              </div>
            </div>
          </div>
          <!--  -->
          <div class="accordion-item">
            <h2 class="accordion-header" id="headingFTTS">
              <button
                class="accordion-button collapsed"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#collapseFTTS"
                aria-expanded="false"
                aria-controls="collapseFTTS"
              >
                <strong>Fiber to the Street</strong>
              </button>
            </h2>
            <div
              id="collapseFTTS"
              class="accordion-collapse collapse"
              aria-labelledby="headingFTTS"
              data-bs-parent="#accordionJob"
            >
              <div class="accordion-body text-start">
                <p class="justified-text">
                  Network 41 AG, the company where I made my apprenticeship and
                  worked for two years, offers engineering services for Swisscom
                  AG and their fiber to the street (FTTS) cable internet rollout
                  in all of Switzerland. The plan is to shorten the distance of
                  the copper wire by bringing fiber optic cables to the street
                  in front of our houses. There, inside a shaft, the light
                  signal gets converted, with so-called mCANs, into the usual
                  copper signal. I was fortunate to receive several further
                  trainings to work with the Swisscom project management tool.
                  Followed by that, I then became a technical project manager
                  for some of the villages where this rollout took place.
                </p>
              </div>
            </div>
          </div>
          <!--  -->
          <div class="accordion-item">
            <h2 class="accordion-header" id="headingMobile">
              <button
                class="accordion-button collapsed"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#collapseMobile"
                aria-expanded="false"
                aria-controls="collapseMobile"
              >
                <strong>Mobile Antennas</strong>
              </button>
            </h2>
            <div
              id="collapseMobile"
              class="accordion-collapse collapse"
              aria-labelledby="headingMobile"
              data-bs-parent="#accordionJob"
            >
              <div class="accordion-body text-start">
                <p class="justified-text">
                  Next to the before mentioned FTTS rollout, Network 41 AG also
                  provides the Swisscom AG with engineering services regarding
                  their mobile internet expansion. When a new location for a
                  mobile antenna has been set, there are many technical
                  conditions that need to be fulfilled. One of them is the
                  electrical power supply. For that reason, I was able to visit
                  several locations in the German-speaking part of Switzerland
                  where I had to do on-site clarifications and plan out the
                  electrical power supply to fit the needs of the mobile
                  antenna.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- paragraph with university accordion -->
      <div class="col">
        <h1 class="pb-3 fw-bold">UNIVERSITY</h1>
        <div class="accordion" id="accordionUniversity">
          <div class="accordion-item">
            <h2 class="accordion-header" id="headingPREN1">
              <button
                class="accordion-button"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#collapsePREN1"
                aria-expanded="true"
                aria-controls="collapsePREN1"
              >
                <strong>Project Unit 1 - Concept: Gravel Cleaner Robot</strong>
              </button>
            </h2>
            <div
              id="collapsePREN1"
              class="accordion-collapse collapse show"
              aria-labelledby="headingPREN1"
              data-bs-parent="#accordionUniversity"
            >
              <div class="accordion-body text-start">
                <p class="justified-text">
                  This mandatory unit provided thorough knowledge of project
                  management and teamwork. Furthermore, it taught their students
                  on how to tackle a problem and find the most economic and
                  environmentally friendly solution to it. The object of the
                  project was to create a concept of a gravel cleaning robot.
                  The project was approached in a team of seven members which
                  interdisciplinary consists of the three departments electrical
                  engineering, mechanical engineering and software engineering.
                  The documentation (in German) can be downloaded and read at
                  the following link:
                </p>
                <button
                  @click="
                    openFileInNewWindow(
                      'Schlussbericht_PREN_1_Team_07_06.01.2023.pdf'
                    )
                  "
                  type="button"
                  class="btn btn-primary"
                  style="
                    background-color: #f67280;
                    color: white;
                    border: #f67280;
                  "
                >
                  Documentation
                </button>
              </div>
            </div>
          </div>
          <!--  -->
          <div class="accordion-item">
            <h2 class="accordion-header" id="headingPREN2">
              <button
                class="accordion-button collapsed"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#collapsePREN2"
                aria-expanded="false"
                aria-controls="collapsePREN2"
              >
                <strong
                  >Project Unit 2 - Realization: Gravel Cleaner Robot</strong
                >
              </button>
            </h2>
            <div
              id="collapsePREN2"
              class="accordion-collapse collapse"
              aria-labelledby="headingPREN2"
              data-bs-parent="#accordionUniversity"
            >
              <div class="accordion-body text-start">
                <p class="justified-text">
                  This mandatory unit builds up on the concept of the last one.
                  The object was to build the concept that had been evaluated in
                  the first project unit. Realizing a concept is always harder
                  than expected. Still, our team managed to overcome all the
                  hurdles and even won the final contest, where all 26 teams
                  competed against each other. Furthermore, it has to be noted
                  that our team has achieved the best grade as only team of them
                  26 in both project units. As before, the documentation (in
                  German) can be downloaded and read at the following link:
                </p>
                <button
                  @click="
                    openFileInNewWindow(
                      'Schlussbericht_PREN_2_Team_07_10.06.2023.pdf'
                    )
                  "
                  type="button"
                  class="btn btn-primary"
                  style="
                    background-color: #f67280;
                    color: white;
                    border: #f67280;
                  "
                >
                  Documentation
                </button>
              </div>
            </div>
          </div>
          <!--  -->
          <div class="accordion-item">
            <h2 class="accordion-header" id="headingSmoke">
              <button
                class="accordion-button collapsed"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#collapseSmoke"
                aria-expanded="false"
                aria-controls="collapseSmoke"
              >
                <strong>Electronics 2 - Smoke Detector</strong>
              </button>
            </h2>
            <div
              id="collapseSmoke"
              class="accordion-collapse collapse"
              aria-labelledby="headingSmoke"
              data-bs-parent="#accordionUniversity"
            >
              <div class="accordion-body text-start">
                <p class="justified-text">
                  This mandatory unit provides intermediate knowledge of all
                  electronic building blocks, like transistors, operational
                  amplifiers, oscillators, AD- & DA-converters, filters, noise
                  and PCB design. There was also a project due, to be able to
                  implement what we learned. In a team of two, we built a
                  complete and functioning optical smoke detector. The
                  documentation (in German) can be downloaded and read at the
                  following link:
                </p>
                <button
                  @click="
                    openFileInNewWindow(
                      'Dokumentation_ELO2_Gruppe_9_Rauchmelder.pdf'
                    )
                  "
                  type="button"
                  class="btn btn-primary"
                  style="
                    background-color: #f67280;
                    color: white;
                    border: #f67280;
                  "
                >
                  Documentation
                </button>
              </div>
            </div>
          </div>
          <!--  -->
          <div class="accordion-item">
            <h2 class="accordion-header" id="headingRogowski">
              <button
                class="accordion-button collapsed"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#collapseRogowski"
                aria-expanded="false"
                aria-controls="collapseRogowski"
              >
                <strong>Advanced Electronics - Rogowski Coil</strong>
              </button>
            </h2>
            <div
              id="collapseRogowski"
              class="accordion-collapse collapse"
              aria-labelledby="headingRogowski"
              data-bs-parent="#accordionUniversity"
            >
              <div class="accordion-body text-start">
                <p class="justified-text">
                  This voluntary unit exists to deepen the learned knowledge
                  from electronics two and to provide further studies in the
                  topics noise, PCB design and known problems and applications
                  in the economy. As well as in the unit electronics two, there
                  was also a project due. This time, also in a team of two, we
                  built a rogowski coil to measure alternating current (AC) at a
                  frequency of 50 Hz. The documentation (in German) can be
                  downloaded and read at the following link:
                </p>
                <button
                  @click="
                    openFileInNewWindow(
                      'Dokumentation_AE_Gruppe_Orange_Rogowskispule.pdf'
                    )
                  "
                  type="button"
                  class="btn btn-primary"
                  style="
                    background-color: #f67280;
                    color: white;
                    border: #f67280;
                  "
                >
                  Documentation
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- paragraph with private accordion -->
      <div class="col">
        <h1 class="pb-3 fw-bold">PRIVATE</h1>
        <div class="accordion" id="accordionPrivate">
          <div class="accordion-item">
            <h2 class="accordion-header" id="headingPortfolio">
              <button
                class="accordion-button"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#collapsePortfolio"
                aria-expanded="true"
                aria-controls="collapsePortfolio"
              >
                <strong>This Portfolio Website</strong>
              </button>
            </h2>
            <div
              id="collapsePortfolio"
              class="accordion-collapse collapse show"
              aria-labelledby="headingPortfolio"
              data-bs-parent="#accordionPrivate"
            >
              <div class="accordion-body text-start">
                <p class="justified-text">
                  Whilst in my studies at HSLU, I already had two units
                  regarding the development of websites. To further deepen this
                  knowledge and have a benefit out of that, I decided to create
                  my own portfolio website. Though, this is not typical for an
                  electrical engineer, I think it is a great idea to further
                  show off one of my many skill sets. In the future, this
                  website might even be completely overhauled and serve an
                  entirely different purpose.
                </p>
                <a href="https://merlin-blickisdorf.ch" target="_blank"
                  >My portfolio website</a
                ><br />
              </div>
            </div>
          </div>
          <!--  -->
          <div class="accordion-item">
            <h2 class="accordion-header" id="headingPower">
              <button
                class="accordion-button collapsed"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#collapsePower"
                aria-expanded="false"
                aria-controls="collapsePower"
              >
                <strong>Lab Power Supply V2</strong>
              </button>
            </h2>
            <div
              id="collapsePower"
              class="accordion-collapse collapse"
              aria-labelledby="headingPower"
              data-bs-parent="#accordionPrivate"
            >
              <div class="accordion-body text-start">
                <p class="justified-text">
                  In the first semester of my studies in electrical engineering,
                  I built a very simple lab power supply. It has been used
                  intensively in the testing phase of the first project unit.
                  Realizing how handy such a power supply is, I wanted the first
                  version to be overhauled because of it not being equipped with
                  all the features I wished it to have. The second version was
                  designed using Fusion 360 and 3D-printed with my own printer
                  at home. Key information, photos and circuitry can be found in
                  the following project overview.
                </p>
              </div>
            </div>
          </div>
          <!--  -->
          <div class="accordion-item">
            <h2 class="accordion-header" id="headingDesk">
              <button
                class="accordion-button collapsed"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#collapseDesk"
                aria-expanded="false"
                aria-controls="collapseDesk"
              >
                <strong>Desk-PC</strong>
              </button>
            </h2>
            <div
              id="collapseDesk"
              class="accordion-collapse collapse"
              aria-labelledby="headingDesk"
              data-bs-parent="#accordionPrivate"
            >
              <div class="accordion-body text-start">
                <p class="justified-text">
                  Whilst in the middle of the corona time (summer 2020), I got
                  bored and built a desk pc. The clue is, that all computer
                  hardware is completely hidden inside the desk and not visible
                  at first glance. For that reason, I had to build the desk from
                  scratch. Furthermore, the issue of cooling had to be
                  addressed. Because of the minimal height of 9 cm inside the
                  desk, no tower cooler could be installed. Consequently, a
                  water cooling system has been put in place. In the following
                  carousel, a few photos of the process can be seen.
                </p>
              </div>
            </div>
          </div>
          <!--  -->
          <div class="accordion-item">
            <h2 class="accordion-header" id="headingVenti">
              <button
                class="accordion-button collapsed"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#collapseVenti"
                aria-expanded="false"
                aria-controls="collapseVenti"
              >
                <strong>Portable Ventilator</strong>
              </button>
            </h2>
            <div
              id="collapseVenti"
              class="accordion-collapse collapse"
              aria-labelledby="headingVenti"
              data-bs-parent="#accordionPrivate"
            >
              <div class="accordion-body text-start">
                <p class="justified-text">
                  By repurposing an old PC-Fan, I've created a simple new
                  product that keeps me cool in hot summers. It has a 5 V micro
                  USB plug that can be powered by any phone charger. Because of
                  the large fan size of 200 mm, the fan is not noisy at all and
                  can still deliver a fair amount of air. To easily place it
                  everywhere, a tripod of an old selfie stick has been
                  repurposed to be the stand of this fan. Therefore, the fan can
                  be placed on all flat surfaces, and the height can
                  additionally be adjusted. This fan is fairly simple and easy
                  to build, but still, some thought had to be put in to create
                  this fan.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HomeProjects",
  props: {
    msg: String,
  },
  methods: {
    openFileInNewWindow(fileName) {
      // Use a relative path to the existing PDF file
      const filePath = "../assets/documents/" + fileName;
      // Open the file in a new window
      window.open(filePath, "_blank");
    },
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.projects {
  background-color: #354f52;
}
.justified-text {
  text-align: justify;
}
/* This sets the container height to the current display height */
.container-fluid {
  height: 100vh;
}
</style>
