<template>
  <main>
   <section class="protocol">
    <div class="container">
      <div class="row">
        <div class="col-lg-6 col-md-6 col-sm-12">
 <div class="protocol-content">

 

          <div class="snap-content"> 
                <img class="snap" src="@/assets/imgs/snap.png"> <h2>Introduction video</h2> 
                </div>
                 <h1>A protocol for creating<br> of new native coins </h1>
             

              <p>PeopleMint gives everyone a chance to participate in <br>coin creation using a resource (a bank note) that is<br> both valuable and accessible to all classes of people.</p>
              

             <br> 
              <a href="">Find out how it works ↓</a>
              
         </div>
        
        </div>

         
 
         <div class="col-lg-6 col-md-6 col-sm-12">
         <img class="header-img" src="@/assets/imgs/header-img.png">
        </div>
      </div>
    </div>




   </section>

    
  </main>
</template>


<script>
import WhitepaperStrip from "~/components/WhitepaperStrip.vue";
import Header2 from "~/components/Header2.vue";
import JoinCommunity from "~/components/JoinCommunity.vue";

export default {
  head() {
    return {
      title: "Ellcrys"
    };
  },
  components: {
    WhitepaperStrip,
    Header2,
    JoinCommunity
  }
};
</script>


<style lang="scss">
@import "@/assets/bootstrap/scss/_functions.scss";
@import "@/assets/bootstrap/scss/_variables.scss";
@import "@/assets/bootstrap/scss/mixins/_breakpoints.scss";
@import "@/assets/css/scss/detail.scss";
@import '@/assets/css/scss/ieo.scss';
</style>

