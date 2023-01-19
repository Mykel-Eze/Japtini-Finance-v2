<template>
  <div id="join-us-page" class="other-pages">
    <!---=== Home Section ===--->
    <section id="home">
      <div class="row full-height">
        <div class="container full-height">
          <div class="home-txt-wrapper">
            <h1 class="home-txt-title">
              Join Us
            </h1>
          </div>
        </div>
      </div>
    </section>
    <!---=== end of Home Section ===--->

    <!---=== Buid-With-Us Section ===--->
    <section id="build-with-us">
      <div class="row">
        <div class="container">
          <div class="bwu-wrapper">
            <div class="bwu-txt-side">
              <div class="bwu-title-side">
                Build with us
              </div>
              <p>
                Japtini Asset Finance is part of a network of nine standalone solutions providers, each with the
                common purpose of supporting communities and enabling farmers and SMEs to increase output.
              </p>
              <p>
                Each of the nine businesses interconnect and synergise to enable Japtini Asset Finance to
                optimise its services.
              </p>
              <p>
                Our network of solutions providers operate in the fields of agriculture, crop services, energy,
                logistics, haulage, financial technology and insurance.
              </p>
              <p class="bold-txt">
                Together, we build dynamic partnerships for mutual problem solving.
              </p>

              <div class="bwu-btn-wrapper">
                <nuxt-link to="/contact-us" class="bwu-btn">
                  Join Us
                </nuxt-link>
              </div>
            </div>
            <div class="bwu-img-side">
              <img src="~/assets/images/happy-team.png" alt="happy team" class="bwu-img">
            </div>
          </div>
        </div>
      </div>
    </section>
    <!---=== end of Buid-With-Us Section ===--->

    <!---=== Stakeholders Section ===--->
    <section id="stakeholders">
      <div class="row">
        <div class="container">
          <div class="stakeholders-wrapper">
            <div class="stakeholders-block">
              <nuxt-link to="/contact-us">
                <img src="~/assets/images/frame-1.jpg" alt="frame" class="stakeholder-img">
              </nuxt-link>
            </div>
            <div class="stakeholders-block">
              <nuxt-link to="/contact-us">
                <img src="~/assets/images/frame-2.jpg" alt="frame" class="stakeholder-img">
              </nuxt-link>
            </div>
            <div class="stakeholders-block">
              <nuxt-link to="/contact-us">
                <img src="~/assets/images/frame-3.jpg" alt="frame" class="stakeholder-img">
              </nuxt-link>
            </div>
            <div class="stakeholders-block">
              <nuxt-link to="/contact-us">
                <img src="~/assets/images/frame-4.jpg" alt="frame" class="stakeholder-img">
              </nuxt-link>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!---=== end of Stakeholders Section ===--->
  </div>
</template>

<script>
export default {
  name: 'JoinUsPage'
}
</script>

<style src="../assets/css/home.css"></style>
<style src="../assets/css/join.css"></style>

<style scoped>
#home {
  background-image: url("../assets/images/join-us-bg.jpg");
  height: 70vh;
  min-height: 400px;
}

@media (max-width: 600px) {
  h1.home-txt-title {
    font-size: 64px;
    line-height: 67px;
  }
}
</style>
