<template>
  <div id="app">
    <div class="intro-section">
      <NavBar/>
    </div>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    
}
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.intro-section{
  height: 100vh;
  background-color: #333333;
}
</style>
