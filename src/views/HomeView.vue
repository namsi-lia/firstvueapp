<template>
 <div class="w3-center content" id="content" >
    <div class=" news-left-align news-margin-top news-info ">
       <h3 style="font-weight: 800;" class="content-head">Arboretum News</h3> 
       <img alt="Our Logo" src="../assets/uhuru-2.jpg" style="width:100px;height:100px;" >
      </div>
       <div class="content-left-align content-margin-top news-info" >
          <br>
          <div class="content-margin-to  content-left-align" >
          <p>
            President Uhuru Kenyatta toured Nairobi Arboretum on June 5, 2020,</p>
            <p> to mark World Environment Day, observed on the 5th of June every year,</p> 
            <p>and has been celebrated for the last 45 years.</p>
          <p>During the event at Nairobi Arboretum, President Kenyatta promised to</p> 
          <p>expand the number and size of conservancies, arboreta, parks and wildlife</p>
          <p>reserves to ensure the country’s botanical and zoological diversity 
           is maintained.</p> 
          <p> “We are also reclaiming our Ngong Forest and we are going to start the 
           process of fencing it and ensuring that it is also available not only</p>
            <p>for the present but for future generations. </p>
          <p>“We have done in the last one month another 2,000 acres for Nairobi National Park 
          and this is what we want to continue doing including restoration of"</p>
          <p>various green areas among them rehabilitation of City Park,” 
          the President stated.</p>
          </div>             
         </div> 
     </div> ``
</template>

<script>
import { defineComponent } from 'vue';

// Components
import HelloWorld from '../components/HelloWorld.vue';

export default defineComponent({
  name: 'HomeView',

  components: {
    HelloWorld,
  },
});
</script>
<style scoped="">
content{
  padding:299px 0px;
  width:100%;
  top: 595px;
  height:425px ;
  margin: auto;
  display:flex;
  justify-content: space-evenly;
  flex-wrap: wrap; 
  background-color: rgb(255, 255, 255); 
  border: 1px solid #000000;
}
</style>