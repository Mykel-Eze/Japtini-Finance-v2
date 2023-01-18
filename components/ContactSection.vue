<template>
  <div id="contact-section">
    <div class="row mag-0">
      <div class="contact-section-wrapper">
        <div class="container">
          <div class="csw-txt-side">
            <h4 class="csw-txt-title section-title">
              We are always happy to help!
            </h4>
            <div class="csw-txt-desc">
              With ample years of experience in solar energy services, our products are designed for the specific
              needs of a customer and adjusted to each person’s unique requirements. We also understand the
              importance of regular upgrades in technology and performance analysis - which ensures that we serve
              our clients with ease.
            </div>
            <div class="csw-btn-wrapper">
              <nuxt-link to="/contact-us" class="csw-btn">
                Contact Us
              </nuxt-link>
            </div>
          </div>
          <div class="csw-img-side">
            <img src="~/assets/images/contact-lady.jpg" alt="contact laddy" class="csw-img">
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ContactSection'
}
</script>

<style scoped>
div#contact-section {
  background: #0d1703;
  color: white;
  padding: 0 0 60px;
}

.contact-section-wrapper {
  position: relative;
}

.contact-section-wrapper::before {
  position: absolute;
  content: "";
  width: 30%;
  height: 100%;
  right: 0;
  top: 0;
  background-image: url("../assets/images/contact-lady.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
}

.contact-section-wrapper > .container {
  display: grid;
  grid-template-columns: 1fr 30%;
  align-items: center;
  gap: 30px;
}

.csw-txt-desc {
  font-size: 18px;
}

img.csw-img {
  visibility: hidden;
}

.csw-btn-wrapper {
  margin-top: 24px;
}

a.csw-btn {
  width: 150px;
  height: 50px;
  line-height: 50px;
  background-color: var(--pry-color);
  color: white;
  display: block;
  text-align: center;
  font-size: 16px;
  letter-spacing: -0.02em;
  font-family: var(--font-medium);
}

a.csw-btn:hover {
  background: #31590a;
}

@media (max-width: 600px) {
  .contact-section-wrapper > .container {
    grid-template-columns: 100%;
  }

  .contact-section-wrapper::before {
    display: none;
  }

  img.csw-img {
    visibility: visible;
  }
}
</style>
