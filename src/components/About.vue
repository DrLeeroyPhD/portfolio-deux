<template>
  <div id="About">
   
   <h1>get to know me</h1>
    
    <p>Hailing from the Portland OR region, I've been immersed in the tech
realm all my life. At the ripe age of eight, I began my quest into the
word of code by developing my first site, utilizing the technologies of
the fading nighties and early aughts, and kept going from there.
If I ever find any spare time, I enjoy programming the raspberry pi to do
all sorts of crazy things, and researching new coding languages.</p>
    
  </div>
</template>

<script>
export default {
  name: 'About',
  data () {
    return {
      msg: 'About Loaded'
    }
  }
}
</script>


<style>
  
  div#About{
    width: 80%;
    margin-left: 10%;
    text-align: center;
    margin-top: 200px;
  }
  
  #About h1{
    font-size: 5em;
    font-family: 'Inconsolata', monospace;
    padding: 50px 10px;
    background-color: #c9c916;
    font-weight: bolder;
  }
  
  #About p{
    font-size: 2.5em;
    text-shadow: 1px 1px 1px #fff;
  }
  
</style>