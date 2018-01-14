<template>
  <div id="app">
    <Navigation></Navigation>
    <Hero></Hero>
    <GrayBarRight></GrayBarRight>
    <About></About>
    <GrayBarLeft></GrayBarLeft>
    <Projects></Projects>
  </div>
</template>

<script>
import Navigation from './components/Navigation.vue'
import Hero from './components/Hero.vue'
import GrayBarRight from './components/GrayBarRight.vue'
import About from './components/About.vue'
import GrayBarLeft from './components/GrayBarLeft.vue'
import Projects from './components/Projects.vue'

export default {
  name: 'app',
  components: {
    Navigation,
    Hero,
    GrayBarRight,
    About,
    GrayBarLeft,
    Projects
  }
}
</script>
