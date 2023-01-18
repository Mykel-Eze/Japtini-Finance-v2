<template>
  <div id="app-wrapper">
    <Navbar />
    <div id="main-contents-wrapper">
      <Nuxt />
    </div>
    <ContactSection />
    <Footer />
  </div>
</template>

<script>
import $ from 'jquery'

import Navbar from '~/components/Navbar'
import Footer from '~/components/Footer'
import ContactSection from '~/components/ContactSection.vue'
export default {
  name: 'DefaultLayout',
  components: { Navbar, Footer, ContactSection },
  mounted () {
    $(window).scroll(function () {
      $('nav.main-nav').toggleClass('scrolled-nav', $(this).scrollTop() > 50)
    })
  }
}
</script>

<style>
div#nav {
  float: left;
  width: 100%;
  overflow-x: hidden;
  position: relative;
  min-height: 100vh;
}
</style>
