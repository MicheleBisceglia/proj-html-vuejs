<template>
  <section>
    <div class="container bg-section">
      <div class="row justyfy-content-center">
        <div class="offset-4 col-4 text-center">
          <p>FIND THE BEST ANIMAL SUPPLIES</p>
          <h2>New arrivals Weekly</h2>
          <button class="btn btn-light rounded-pill">Learn more about us</button>
        </div>
      </div>
    </div>
    
    <div class="container">
      
      <div class="row">
        <div class="col-6">
          <p class="pt-5">All-time sellers</p>
          <h3>Items evryone loves</h3>
        </div>
        <div class="col-6 text-end">
          <button class="btn btn-success rounded-pill mt-5">View all products</button>
        </div>
      </div>

      <div class="row">
        <div class="col-3">
          <img class="w-100 pt-5" src="../assets/img/product-21-600x600.jpg" alt="">
          <p class="text-center pt-3">Transport Cage</p>
        </div>
        <div class="col-3">
          <img class="w-100 pt-5" src="../assets/img/product-20-600x600.jpg" alt="">
          <p class="text-center pt-3">Dog Leash</p>
        </div>
        <div class="col-3">
          <img class="w-100 pt-5" src="../assets/img/product-16-600x600.jpg" alt="">
          <p class="text-center pt-3">Animal transport cage</p>
        </div>
        <div class="col-3">
          <img class="w-100 pt-5" src="../assets/img/product-11-600x600.jpg" alt="">
          <p class="text-center pt-3 pb-5">Colorful cat leash</p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "SecondSection",
}
</script>

<style lang="scss" scoped>
@import "../style/common.scss";
.bg-section {
  background-image: url(../assets/img/banner-3-2x-scaled.jpg);
  height: 400px;
  background-size: cover;
  color: white;
  p {
    margin-top: 150px;
  }
}
</style>