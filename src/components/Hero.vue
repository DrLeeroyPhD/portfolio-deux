<template>
  <div id="Hero">
   
   
    <div id="hero-content">
      <img src="./img/title-computer.png" alt="Fill Murray" />
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
    margin-bottom: 20px;
    z-index: 1;
  }
  
  #Hero h1{
    font-family: var(--anton);
    font-size: 3em;
    letter-spacing: 2px;
    color: var(--main-gray);
    text-shadow: 1px 1px 1px #fff;
  }
  
  #Hero h2{
    font-family: var(--kanit);
    font-size: 2em;
    color: var(--main-gray);
    text-shadow: 1px 1px 1px #fff;
  }
  
</style>