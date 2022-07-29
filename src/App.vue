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
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import Intro from './components/IntroSection.vue'
import AboutSection from './components/AboutSection.vue'
import SearchSection from './components/SearchSection.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    Intro,
    AboutSection,
    SearchSection
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
</style>
