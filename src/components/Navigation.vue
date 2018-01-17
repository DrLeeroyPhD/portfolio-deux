<template>
  <div id="Navigation">
    <nav>
      <ul>
        <a href="#Navigation">
          <li>HOME</li>
        </a>
        <a href="#About">
          <li>ABOUT</li>
        </a>
        <a href="#Projects">
          <li>PROJECTS</li>
        </a>
        <a href="#Contact">
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
    background-color: #FFD54F;
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
  
  
</style>
