<template>
  <div id="GrayBarMiddle">
    
   
  </div>
</template>

<script>
export default {
  name: 'GrayBarMiddle',
  data () {
    return {
      msg: 'GrayBarMiddle Loaded'
    }
  }
}
</script>


<style scoped>
  
  #GrayBarMiddle{
    top: 160%;
    left: 0;
    position: absolute;
    display: inline;
    z-index: -2000;
    height: 0;
    width: 0;
    border-top: 400px solid transparent;
    border-bottom: 800px solid transparent; 
    border-left: 15vw solid var(--main-gray);
    overflow: hidden;
  }
  
</style>