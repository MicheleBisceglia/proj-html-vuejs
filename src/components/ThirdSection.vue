<template>
  <section class="bg-section">
    <div class="my_title">
      <h3 class="text-center">Users Testimonials</h3>
    </div>
    <div class="container">
      <div class="row">
        <div class="col-4 text-center pt-5">
          <img class="w-25 rounded-pill" src="../assets/img/avatar-3-600x600.jpg" alt="">
          <p class="pt-3 text-light">Auctor est habitasse amet nunc, interdum vel mattis sodales cras. Ut nulla quis nunc, tincidunt eu. Eu.</p>
        </div>
        <div class="col-4 text-center pt-5">
          <img class="w-25 rounded-pill" src="../assets/img/avatar-1.jpg" alt="">
          <p class="pt-3 text-light">Donec sollicitudin molestie malesuada. Vivamus suscipit tortor eget felis porttitor volutpat vestibulum ac diam sit.</p>
        </div>
        <div class="col-4 text-center pt-5">
          <img class="w-25 rounded-pill" src="../assets/img/avatar-4-600x600.jpg" alt="">
          <p class="pt-3 text-light">Curabitur arcu erat, accumsan id imperdiet et, porttitor at sem. Proin eget tortor risus vestibulum ante ipsum.</p>
        </div>
      </div>
    </div>
    <div class="">
      <div class="my_container pt-5">
       <div class="container">
         <div class="row">
           <div class="col-6"></div>
           <div class="col-6"></div>
         </div>
       </div>
        
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "ThirdSection",
}
</script>

<style lang="scss" scoped>
@import "../style/common.scss";
  .bg-section {
    height: 350px;
    width: 100%;
    background-color: $secondary-color;
    background-image: url(../assets/img/bg-transparent-3.png);
  .my_title {
    color: white;
    padding-top: 70px;
  }
  }
.my_container {
  width: 80%;
  height: 80%;
  margin: 0 auto;
  background-image: url(../assets/img/banner-7-2x-scaled.jpg);
 

}
</style>