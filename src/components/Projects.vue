<template>
  <div id="Projects">
   
   
    <div><img src="https://www.fillmurray.com/300/300" alt="Fill Murray" class="myWork" /></div>
    
    <div id="projectGallery">
      <a href="#"><img src="http://via.placeholder.com/350x250" alt=""></a>
      <a href="#"><img src="http://via.placeholder.com/350x250" alt=""></a>
      <a href="#"><img src="http://via.placeholder.com/350x250" alt=""></a>
      <a href="#"><img src="http://via.placeholder.com/350x250" alt=""></a>
      <a href="#"><img src="http://via.placeholder.com/350x250" alt=""></a>
      <a href="#"><img src="http://via.placeholder.com/350x250" alt=""></a>
    </div>
    
  </div>
</template>

<script>
export default {
  name: 'Projects',
  data () {
    return {
      msg: 'Projects Loaded'
    }
  }
}
</script>


<style>
  
  div#Projects{
    margin-top: 200px;
    width: 90%;
    margin-left: 5%;
    display: grid;
    grid-template-columns: 1fr 9fr;
    grid-template-rows: 1fr;
    align-items: center;
  }
  
  #projectGallery{
    display: grid;
    grid-template-rows: 1fr 1fr;
    grid-template-columns: 1fr 1fr 1fr;
  }
  
  img.myWork{
    margin-right: 10px;
    border-radius: 50%;
  }
  
</style>