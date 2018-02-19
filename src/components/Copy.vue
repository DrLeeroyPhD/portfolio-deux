<template>
  <div id="Copy">
   
    <h2>WWW.SWEETWEBSITEBRO.COM</h2>

    
  </div>
</template>

<script>
export default {
  name: 'Copy',
  data () {
    return {
      msg: 'Copy Loaded'
    }
  }
}
</script>


<style scoped>
  #Copy{
    width: 100%;
    background-color: var(--main-yellow);
    margin-bottom: 0;
    display: flex;
    justify-content: center;
  }
  
  #Copy h2{
    color: #fff;
    font-size: 2em;
    font-family: 'Inconsolata', monospace;
    transition: .25s color;
  }
  
  #Copy h2:hover{
    color: var(--main-gray);
    transition: .25s color;
  }
</style>