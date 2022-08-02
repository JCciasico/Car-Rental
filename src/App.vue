<template>
  <div id="app">
    <div class="intro-section">
      <NavBar/>
      <Intro/>
    </div>
    <div class="about-sec">
      <AboutSection/>
    </div>
    <div class="search-section">
      <SearchSection/>
    </div>
    <div class="services-section">
      <ServicesSection/>
    </div>
    <div class="rent-section">
      <RentSection/>
    </div>
    <div class="dashboard-section">
      <DashBoard/>
    </div>
    <div class="blog-section">
      <BlogSection/>
    </div>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import Intro from './components/IntroSection.vue'
import AboutSection from './components/AboutSection.vue'
import SearchSection from './components/SearchSection.vue'
import ServicesSection from './components/ServicesSection.vue'
import RentSection from './components/RentSection.vue'
import DashBoard from './components/DashBoard.vue'
import BlogSection from './components/BlogSection.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    Intro,
    AboutSection,
    SearchSection,
    ServicesSection,
    RentSection,
    DashBoard,
    BlogSection
}
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app{
  overflow: hidden;
}
.intro-section{
  background-color: #333333;
}
.services-section{
  background-image: url(./assets/download.jfif);
  background-repeat: no-repeat;
  background-size: cover;
  background: linear-gradient(rgba(0, 0, 0, 0.9),rgba(0, 0, 0, 0.75),rgba(0, 0, 0, 0.9)), 
	url("./assets/download.jfif");
}
.dashboard-section{
  background-image: url(./assets/download.jfif);
  background-repeat: no-repeat;
  background-size: cover;
  background: linear-gradient(rgba(0, 0, 0, 0.9),rgba(0, 0, 0, 0.75),rgba(0, 0, 0, 0.9)), 
	url("./assets/lotus.jpg");
}
</style>
