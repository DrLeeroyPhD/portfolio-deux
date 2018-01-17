<template>
  <div id="GrayBarLeft">
   
   
  </div>
</template>

<script>
export default {
  name: 'GrayBarLeft',
  data () {
    return {
      msg: 'GrayBarLeft Loaded'
    }
  }
}
</script>


<style scoped>
  
  #GrayBarLeft{
    top: 160%;
    left: 0;
    position: absolute;
    display: inline;
    z-index: -2000;
    height: 0;
    width: 0;
    border-top: 400px solid transparent;
    border-bottom: 400px solid transparent; 
    border-left: 15vw solid var(--main-gray);
    overflow: hidden;
  }
  
</style>