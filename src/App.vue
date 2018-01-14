<template>
  <div id="app">
    <Navigation></Navigation>
    <Hero></Hero>
    <GrayBarRight></GrayBarRight>
    <About></About>
    <GrayBarLeft></GrayBarLeft>
  </div>
</template>

<script>
import Navigation from './components/Navigation.vue'
import Hero from './components/Hero.vue'
import GrayBarRight from './components/GrayBarRight.vue'
import About from './components/About.vue'
import GrayBarLeft from './components/GrayBarLeft.vue'

export default {
  name: 'app',
  components: {
    Navigation,
    Hero,
    GrayBarRight,
    About,
    GrayBarLeft
  }
}
</script>
