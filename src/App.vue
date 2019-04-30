<template lang="html">
  <div id="app">
      <div class="bg-sp text-white">
          <navigation></navigation>
          <home></home>
          <div class="container-fluid mt-5">
            <div class="row">
              <div class="col-md-12">
                <about></about>
              </div>
            </div>
            <div class="row">
              <div class="col-md-12">
                <skills></skills>
              </div>
            </div>
            <div class="row">
              <div class="col-md-12">
                <experince></experince>
              </div>
            </div>
            <div class="row">
              <div class="col-md-12">
                <protfolio></protfolio>
              </div>
            </div>
            <div class="row">
              <div class="col-md-12">
                <contact></contact>
              </div>
            </div>
            <div class="row">
              <div class="col-md-12">
                <footer></footer>
              </div>
            </div>
          </div>
      </div>
  </div>
</template>

<script>
import Navigation from './Components/Navigation/Navbar.vue'
import Home from './Components/Main/Home.vue'
import About from './Components/Main/About.vue'
import skills from './Components/Main/skills.vue'
import Experince from './Components/Main/Experince.vue'
import Protfolio from './Components/Main/Portfolio.vue'
import Contact from './components/Main/Contact.vue'
import footer from './Components/Navigation/Footer.vue'

export default {

  components :{
    Home,
    Navigation,
    About,
    skills,
    Experince,
    Protfolio,
    Contact,
    footer
  }
}
</script>

<style>
.bg-sp{
  background: #030303; 
}
</style>
