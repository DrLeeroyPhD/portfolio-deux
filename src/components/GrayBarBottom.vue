<template>
  <div id="GrayBarBottomContainer">
    
    <div id="GrayBarBottom"></div>
    
  </div>
  
</template>

<script>
export default {
  name: 'GrayBarBottom',
  data () {
    return {
      msg: 'GrayBarBottom Loaded'
    }
  }
}
</script>


<style scoped>
  
  #GrayBarBottomContainer{
    top: 280%;
    width: 100%;
    margin: 0;
    padding: 0;
    height: 1000px;
    position: absolute;
    overflow: hidden;
    z-index: -2000;
  }
  
  #GrayBarBottom{
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