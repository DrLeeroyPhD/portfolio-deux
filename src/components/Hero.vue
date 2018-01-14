<template>
  <div id="Hero">
   
   
    <div id="hero-content">
      <img src="https://www.fillmurray.com/400/400" alt="Fill Murray" />
      <h1>christopher denny</h1>
      <h2>WEB DEVELOPER</h2>
    </div>

    
  </div>
</template>

<script>
export default {
  name: 'Hero',
  data () {
    return {
      msg: 'Hero Loaded'
    }
  }
}
</script>


<style>
  
  div#Hero{
    display: flex;
    justify-content: space-around;
    text-align: center;
    margin-top: 80px;
  }
  
  #Hero img{
    border-radius: 50%;
  }
  
</style>