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


<style scoped>
  
  div#Hero{
    display: flex;
    justify-content: space-around;
    text-align: center;
    margin-top: 80px;
  }
  
  #Hero img{
    border-radius: 50%;
  }
  
  #Hero h1{
    font-family: 'Anton', sans-serif;
    font-size: 3em;
    letter-spacing: 2px;
    color: var(--main-gray);
  }
  
  #Hero h2{
    font-family: 'Kanit', sans-serif;
    font-size: 2em;
    color: var(--main-gray);
  }
  
</style>