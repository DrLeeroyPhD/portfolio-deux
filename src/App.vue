<template>
  <div id="app">
    <Navigation></Navigation>
    <Hero></Hero>
    <GrayBarTop></GrayBarTop>
    <About></About>
    <GrayBarMiddle></GrayBarMiddle>
    <Projects></Projects>
    <GrayBarBottom></GrayBarBottom>
    <Quote></Quote>
    <Contact></Contact>
    <Copy></Copy>
  </div>
</template>

<script>
import Navigation from './components/Navigation.vue'
import Hero from './components/Hero.vue'
import GrayBarTop from './components/GrayBarTop.vue'
import About from './components/About.vue'
import GrayBarMiddle from './components/GrayBarMiddle.vue'
import Projects from './components/Projects.vue'
import GrayBarBottom from './components/GrayBarBottom.vue'
import Quote from './components/Quote.vue'
import Contact from './components/Contact.vue'
import Copy from './components/Copy.vue'

export default {
  name: 'app',
  components: {
    Navigation,
    Hero,
    GrayBarTop,
    About,
    GrayBarMiddle,
    Projects,
    GrayBarBottom,
    Quote,
    Contact,
    Copy
  }
}
</script>


<style>
  :root {
    --main-gray: #373741;
    --main-yellow: #FFD54F;
    
    --kanit: 'Kanit', sans-serif;
    --anton: 'Anton', sans-serif;
    --archivo: 'Archivo Narrow', sans-serif;
  }
</style>