<template>
  <main>
    <div class="ieo-page">
      
<section class="decentralized">
<div class="container">
  <div class="row">
    <div class="col-lg-7  col-md-7 col-sm-12">
     <h1>The  Powerful Infrastructure for<br>
     Open Decentralized Organizations</h1>
     <br>
       <p><a href=""> Read Whitepaper</a> &nbsp; <img src="@/assets/imgs/nnarrow.png" > </p>
    </div>
    <div class="col-lg-5 col-md-5 col-sm-12">
    <img src="@/assets/imgs/noble.png">
    </div>
    </div>
</div>  

<div class="box-collection">
  <div class="container">
    <div class="row">
      <div class="col-lg-6 col-md-6  col-sm-12 col-xs-12">
  <div class="box">
   <h1>Platform Censorship</h1>
   <br>

   <p>Users are increasingly threatened by the ability of service providers to
      censor opinions that do not resonate with their beliefs or those of their 
      customers. Why censorship of opinions and ideas may be unquestionable in 
      some instances, the power these services wield  can and have deprived many
       users' their rights and means of livelihood.</p>
       <br>
  </div>
      </div>

      <div class="col-lg-6 col-md-6  col-sm-12 col-xs-12">
      <div class="box">
        <h1>Data Ownership & Privacy </h1>
        <br>

        <p>Most platform on the internet allow users to use their services for free. 
          But the catch here is that majority of these platforms sell users' data to 
          third-party agents without clear and explicit consent of users. This practice 
          expose users to intrusive and targetted advertising, identity theft and losses.
           They have no way to truly own, manage and authorize access to their data. </p>
      </div>
      </div>

      
    </div> 
    <br><br>
    <div class="row">
      <div class="col-lg-6 col-md-6  col-sm-12 col-xs-12">
   <div class="box">
     <h1>Single Ownership Architecture</h1>
     <br>
     <p>Collaborative platforms (e.g. code-sharing platforms)
        only support single-owner architecture where one user,
         by default, is granted complete control of all resources - 
         This kind of ownership structure and assumption is not right for
          communities of individuals who share little or nothing in common 
          and have no basis for trust.</p>
   </div>
      </div>

      <div class="col-lg-6 col-md-6  col-sm-12 col-xs-12">
        <div class="box">
    <h1>Shared Ownership</h1>
<br>
    <p> Open communities will create assets and resources that are owned by members.
       There needs to be a mechanism by which ownership is proved, verified and enforced 
       in a transparent and replicable way. Additionally, collective resources need to render 
       themselves to be administered using the governance structure setup by members.</p>
        </div>
      </div>
    </div>
  </div>

</div>
      

  </section>

  <section class="safehold">
<div class="container">
  <div class="row">
    <div class="col-lg-5 col-md-5 col-sm-12">
  <h1>Download <span>SafeHold</span></h1>

  <p><span>SafeHold</span> —  A desktop app for sending, receiving and mining transactions on our network (currently the test network). 
    SafeHold makes accessing Ellcrys functionalities easy and straightforward. </p>

    
 
    

   
  
    </div>
     <div class="col-lg-6 col-md-6 col-sm-12">
      <img src="@/assets/imgs/note.png">
    </div>
  </div>
</div>


  </section>


  <section class="fund">
   <div class="rectangle">
   <div class="row">
    
       <div class="square">
          <a href="#">Token Allocation</a> 
       </div>
       <div class="square-2 float-right">
           <a href="#">Fund Allocation</a> 
       </div>
    
   </div>

   </div>

   <div class="section">

    <img src="@/assets/imgs/fund.png">
   </div>

  



  </section>


 


</div>






    
  </main>
</template>
<script>
$(document).ready(function(){
	alert("segun")
});
</script>

<script>
// import ModalVideo from 'modal-video';

import Header2 from "~/components/Header2.vue";
import Tag from "~/components/Tag.vue";
const links = require("../../../data/links.json");

const UAParser = require("ua-parser-js");

// const videoModal = require("modal-video")


export default {
  components: {
    // Header2,
    // Tag
  },

  head() {
    return {
      title: "SafeHold - Ellcrys"
    };
  },
  data: function() {

  },
  mounted() {

  
  },
  methods: {

  }
};
</script>



<style lang="scss">
@import "@/assets/bootstrap/scss/mixins/_breakpoints.scss";
@import "@/assets/bootstrap/scss/_functions.scss";
@import "@/assets/bootstrap/scss/_variables.scss";
@import "@/assets//css/scss/detail.scss";
@import "@/assets//css/scss/ieo.scss";
</style>
