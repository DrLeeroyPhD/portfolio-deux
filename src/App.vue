<template>
  <div id="app">
    <Navigation></Navigation>
    <Hero></Hero>
    <GrayBarRight></GrayBarRight>
    <About></About>
    <GrayBarLeft></GrayBarLeft>
    <Projects></Projects>
    <GrayBarQuoteTop></GrayBarQuoteTop>
    <Quote></Quote>
    <Contact></Contact>
    <Copy></Copy>
  </div>
</template>

<script>
import Navigation from './components/Navigation.vue'
import Hero from './components/Hero.vue'
import GrayBarRight from './components/GrayBarRight.vue'
import About from './components/About.vue'
import GrayBarLeft from './components/GrayBarLeft.vue'
import Projects from './components/Projects.vue'
import GrayBarQuoteTop from './components/GrayBarQuoteTop.vue'
import Quote from './components/Quote.vue'
import Contact from './components/Contact.vue'
import Copy from './components/Copy.vue'

export default {
  name: 'app',
  components: {
    Navigation,
    Hero,
    GrayBarRight,
    About,
    GrayBarLeft,
    Projects,
    GrayBarQuoteTop,
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
  }
</style>