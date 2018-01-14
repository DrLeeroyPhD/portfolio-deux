<template>
  <div id="GrayBarRight">
   
   

    
  </div>
</template>

<script>
export default {
  name: 'GrayBarRight',
  data () {
    return {
      msg: 'GrayBarRight Loaded'
    }
  }
}
</script>


<style>
  #GrayBarRight{
    top: 80%;
    right: 0;
    position: absolute;
    display: inline;
    z-index: -2000;
    height: 0;
    width: 0;
    border-top: 200px solid transparent;
    border-bottom: 350px solid transparent; 
    border-right: 115vw solid #333;
    overflow: hidden;
  }
</style>