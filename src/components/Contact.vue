<template>
  <div id="Contact">
   
    <img src="https://www.fillmurray.com/800/800" alt="Fill Murray" />

    
  </div>
</template>

<script>
export default {
  name: 'Contact',
  data () {
    return {
      msg: 'Contact Loaded'
    }
  }
}
</script>


<style scoped>
  #Contact{
    display: flex;
    justify-content: center;
    margin-top: 150px;
    margin-bottom: 30px;
  }
  
  #Contact img{
    border-radius: 50%;
  }
</style>