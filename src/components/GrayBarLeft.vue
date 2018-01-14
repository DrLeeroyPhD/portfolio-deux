<template>
  <div id="GrayBarLeft">
   
   
  </div>
</template>

<script>
export default {
  name: 'GrayBarLeft',
  data () {
    return {
      msg: 'Hero Loaded'
    }
  }
}
</script>


<style>
  
  #GrayBarLeft{
    top: 160%;
    left: 0;
    position: absolute;
    display: inline;
    z-index: -2000;
    height: 0;
    width: 0;
    border-top: 350px solid transparent;
    border-bottom: 350px solid transparent; 
    border-left: 15vw solid #333;
    overflow: hidden;
  }
  
</style>