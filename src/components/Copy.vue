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
    margin-top: 30px;
  }
  
  #Copy h2{
    color: #fff;
    font-size: 2em;
    font-family: var(--archivo);
    transition: .25s color;
    letter-spacing: 2px;
  }
  
  #Copy h2:hover{
    color: var(--main-gray);
    transition: .25s color;
  }
</style>