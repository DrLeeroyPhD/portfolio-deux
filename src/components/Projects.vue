<template>
  <div id="Projects">
   
   
    <div><img src="https://www.fillmurray.com/300/300" alt="Fill Murray" class="myWork" /></div>
    
    <div id="projectGallery">
      <a v-for="project in projects" :href="project.url" target="_blank"><img :src="project.image" :alt="project.alt"></a>
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
          image: "http://via.placeholder.com/350x250",
          alt: "Image-link displaying the front page of the Origami of Code website."
        },
        
        // 2
        /***** PDX Fun *****/
        pdxfun: {
          name: "PDX Fun",
          url: "http://www.pdxfun.me/",
          image: "http://via.placeholder.com/350x250",
          alt: "Image-link displaying the front page of the PDX Fun website."
        },
        
        // 3
        /***** Sweet Website Bro *****/
        sweet: {
          name: "Sweet Website Bro",
          url: "",
          image: "http://via.placeholder.com/350x250",
          alt: "Image-link displaying the front page of the classic Sweet Website Bro portfolio website."
        },
        
        // 4
        /***** Sing Along Sidekicks *****/
        sidekicks: {
          name: "Sing-Along Sidekicks",
          url: "http://www.singalongsidekicks.com/",
          image: "http://via.placeholder.com/350x250",
          alt: "Image-link displaying the front page of the Sing-Along Sidekicks website."
        },
        
        // 5
        /***** Material Flow *****/
        material: {
          name: "Material Flow",
          url: "http://www.materialflow.com/",
          image: "http://via.placeholder.com/350x250",
          alt: "Image-link displaying the front page of the Material Flow website."
        },
        
        // 6
        /***** COG7 *****/
        cog7: {
          name: "CoG7 Portland Church",
          url: "http://www.cg7portland.org/",
          image: "http://via.placeholder.com/350x250",
          alt: "Image-link displaying the front page of the Church of God Seventh Day website."
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
    grid-gap: 20px 4%;
    overflow: hidden;
  }
  
  #projectGallery img{
    max-width: 100%;
    border-radius: 15px;
  }
  
  #projectGallery img:hover{
    cursor: pointer;
  }
  
  img.myWork{
    border-radius: 50%;
    justify-self: start;
  }
  
</style>