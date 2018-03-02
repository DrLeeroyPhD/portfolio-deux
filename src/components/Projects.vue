<template>
  <div id="Projects">
   
   
    <div><img src="https://www.fillmurray.com/300/300" alt="Fill Murray" class="myWork" /></div>
    
    <div id="projectGallery">
      <img src="http://via.placeholder.com/350x250" alt="">
      <img src="http://via.placeholder.com/350x250" alt="">
      <img src="http://via.placeholder.com/350x250" alt="">
      <img src="http://via.placeholder.com/350x250" alt="">
      <img src="http://via.placeholder.com/350x250" alt="">
      <img src="http://via.placeholder.com/350x250" alt="">
    </div>
    
  </div>
</template>

<script>
export default {
  name: 'Projects',
  data () {
    return {
      msg: 'Projects Loaded',
      
      // 1
      /***** Origami of Code *****/
      projects: {
        ooc: {
          name: "Origami of Code",
          url: "http://www.origamiofcode.org/",
          image: "",
          alt: ""
        },
        
        // 2
        /***** PDX Fun *****/
        pdxfun: {
          name: "PDX Fun",
          url: "http://www.pdxfun.me/",
          image: "",
          alt: ""
        },
        
        // 3
        /***** Sweet Website Bro *****/
        sweet: {
          name: "Sweet Website Bro",
          url: "",
          image: "",
          alt: ""
        },
        
        // 4
        /***** Sing Along Sidekicks *****/
        sidekicks: {
          name: "Sing-Along Sidekicks",
          url: "http://www.singalongsidekicks.com/",
          image: "",
          alt: ""
        },
        
        // 5
        /***** Material Flow *****/
        material: {
          name: "Material Flow",
          url: "http://www.materialflow.com/",
          image: "",
          alt: ""
        },
        
        // 6
        /***** COG7 *****/
        cog7: {
          name: "CoG7 Portland Church",
          url: "http://www.cg7portland.org/",
          image: "",
          alt: ""
        }
      }
    }
  }
}
</script>


<style scoped>
  
  div#Projects{
    margin-top: 200px;
    width: 90%;
    margin-left: 5%;
    display: grid;
    grid-template-columns: 1fr 9fr;
    grid-template-rows: 1fr;
    align-items: center;
    justify-items: center;
    grid-gap: 10px 10px;
    overflow: hidden;
  }
  
  #projectGallery{
    display: grid;
    grid-template-rows: 1fr 1fr;
    grid-template-columns: 30% 30% 30%;
    grid-gap: 10px;
    overflow: hidden;
  }
  
  #projectGallery img{
    max-width: 100%;
  }
  
  #projectGallery img:hover{
    cursor: pointer;
  }
  
  img.myWork{
    border-radius: 50%;
    justify-self: start;
  }
  
</style>