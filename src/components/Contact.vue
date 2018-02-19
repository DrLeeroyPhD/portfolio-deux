<template>
  <div id="Contact">
    
    <h2>Contact Me!</h2>
    <img src="./img/contact.png" alt="Contact Section" />

    
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
    align-items: center;
  }
  
  #Contact h2{
    font-size: 4em;
    font-family: var(--kanit);
  }
  
</style>