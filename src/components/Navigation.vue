<template>
  <div id="Navigation">
    <nav>
      <ul>
        <a href="#">
          <li>HOME</li>
        </a>
        <a data-scroll href="#About">
          <li>ABOUT</li>
        </a>
        <a data-scroll href="#Projects">
          <li>PROJECTS</li>
        </a>
        <a data-scroll href="#Contact">
          <li>CONTACT</li>
        </a>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'Navigation',
  data () {
    return {
      msg: 'Navigation Loaded'
    }
  }
}
</script>

<style scoped>
  
  div#Navigation{
    background-color: var(--main-yellow);
    margin: 0;
    
  }
  
  #Navigation nav ul{
    display: flex;
    justify-content: space-around;
    flex-direction: row;
    margin: 0;
  }
  
  #Navigation nav ul a{
    text-decoration: none;
    transition: color .25s ease-in-out;
  }
  
  #Navigation nav ul a li{
    list-style: none;
    text-align: center;
    font-family: 'Inconsolata', monospace;
    color: #fff;
    font-size: 2em;
    letter-spacing: 15px;
    transition: color .25s ease-in-out;
    padding: 40px 8px;
  }
  
  #Navigation nav ul a li:hover{
    color: #a8934f;
    transition: color .25s ease-in-out;
  }
  
  
  
  /***** MEDIA QUERIES *****/
  @media screen and (max-width: 1024px) {
    
    #Navigation nav ul a li{
      letter-spacing: 8px;
      font-size: 1.75em;
    }
  }
  
  
  
  
</style>
