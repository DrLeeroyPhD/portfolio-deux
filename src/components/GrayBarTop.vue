<template>
  <div id="GrayBarTop">

    
  </div>
</template>

<script>
export default {
  name: 'GrayBarTop',
  data () {
    return {
      msg: 'GrayBarTop Loaded'
    }
  }
}
</script>


<style scoped>
  #GrayBarTop{
    top: 80%;
    right: 0;
    position: absolute;
    display: inline;
    z-index: -2000;
    height: 0;
    width: 0;
    border-top: 200px solid transparent;
    border-bottom: 350px solid transparent; 
    border-right: 115vw solid var(--main-gray);
    overflow: hidden;
  }
</style>