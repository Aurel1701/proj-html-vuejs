<template>
  <div id="app">
    <FreelancerHeader />
    <AboutMe />
    <RecentWork />
  </div>
</template>

<script>
import FreelancerHeader from './components/FreelancerHeader.vue'
import AboutMe from './components/AboutMe.vue'

export default {
  name: 'App',
  components: {
    FreelancerHeader,
    AboutMe,
    
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
