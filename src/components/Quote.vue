<template>
  <div id="Quote">
   
     <img src="./img/bracket.jpg" alt="Fill Murray" />
     <h2>“Always code as if the
      guy who ends up
      maintaining your code
      will be a violent
      psychopath who knows
      where you live”</h2>
      <h3>JOHN WOODS</h3>
    
  </div>
</template>

<script>
export default {
  name: 'Quote',
  data () {
    return {
      msg: 'Quote Loaded'
    }
  }
}
</script>


<style scoped>
  
  #Quote{
    margin-top: 200px;
    display: grid;
    grid-template-rows: 30% 30% 30%;
    grid-auto-columns: 1fr;
    justify-items: center;
  }
  
  #Quote>img{
    border-radius: 50%;
  }
  
  #Quote>img:hover{
    animation-name: spin;
    animation-duration: 2100ms;
    animation-iteration-count: infinite;
    animation-timing-function: linear;
  }
  
  @keyframes spin {
    from {
        transform:rotate(0deg);
    }
    to {
        transform:rotate(360deg);
    }
}
  
  #Quote>h2{
    font-size: 3em;
    color: #fff;
    text-align: center;
    width: 40%;
    font-family: var(--kanit);
  }
  
  #Quote>h3{
    font-size: 2.5em;
    color: cornflowerblue;
    font-family: var(--anton);
    letter-spacing: 5px;
  }
  
  
  /***** MEDIA QUERIES *****/
  
  @media screen and (max-width: 1090px) { 
    
    #Quote>h2{
      width: 80%;
    }
    
  }
  
</style>