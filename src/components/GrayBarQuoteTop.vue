<template>
  <div id="GrayBarQuoteTopContainer">
    
    <div id="GrayBarQuoteTop"></div>
    
  </div>
  
</template>

<script>
export default {
  name: 'GrayBarQuoteTop',
  data () {
    return {
      msg: 'GrayBarQuoteTop Loaded'
    }
  }
}
</script>


<style scoped>
  
  #GrayBarQuoteTopContainer{
    top: 240%;
    width: 100%;
    margin: 0;
    padding: 0;
    height: 1000px;
    position: absolute;
    overflow: hidden;
    z-index: -2000;
  }
  
  #GrayBarQuoteTop{
    top: 0;
    left: 0;
    position: absolute;
    display: inline;
    z-index: -2001;
    height: 0;
    width: 0;
    border-top: 500px solid transparent;
    border-bottom: 500px solid transparent; 
    border-left: 450vw solid var(--main-gray);
  }
  
</style>