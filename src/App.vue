<template>
  <div id="app">
    <FreelancerHeader />
    <AboutMe />
    <RecentWork />
  </div>
</template>

<script>
import RecentWork from './components/RecentWork.vue'
import FreelancerHeader from './components/FreelancerHeader.vue'
import AboutMe from './components/AboutMe.vue'

export default {
  name: 'App',
  components: {
    FreelancerHeader,
    AboutMe,
    RecentWork,
   
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
