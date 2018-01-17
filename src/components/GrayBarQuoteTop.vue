<template>
  <div id="GrayBarQuoteTop">
   
   
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


<style>
  
  #GrayBarQuoteTop{
    top: 240%;
    left: 0;
    position: absolute;
    display: inline;
    z-index: -2000;
    height: 0;
    width: 0;
    border-top: 500px solid transparent;
    border-bottom: 500px solid transparent; 
    border-left: 450vw solid var(--main-gray);
    overflow: hidden;
  }
  
</style>