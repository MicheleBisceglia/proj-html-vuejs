<template>
  <section class="shop-category text-center mt-5">
  <!-- Category section -->    
    <h2 class="text-center pt-5 pb-3  second-font">Browse by category</h2>
    <p class="w-50 mx-auto pb-5  second-font">Augue purus et, tincidunt condimentum mauris. At nibh rutrum mi in. Nisi, vitae interdum eleifend dui, consequat nulla rhoncus dictum. Viverra.</p>
    
    <div class="container">
      <div class="row">
        <div class="col-3">
          <img class="w-100" src="../assets/img/product-9-600x600.jpg" alt="">
          <p class="text-center pt-3">Bed (1)</p>
        </div>
        <div class="col-3">
          <img class="w-100" src="../assets/img/product-3-600x600.jpg" alt="">
          <p class="text-center pt-3">Food (6)</p>
        </div>
        <div class="col-3">
          <img class="w-100" src="../assets/img/product-2-600x600.jpg" alt="">
          <p class="text-center pt-3">Toys (6)</p>
        </div>
        <div class="col-3">
          <img class="w-100" src="../assets/img/product-4-600x600.jpg" alt="">
          <p class="text-center pt-3 pb-5">Transport (6)</p>
        </div>
      </div>
    </div>
  <!-- /Category section --> 

  <!-- Food Shop section -->
    <div class="container">
      <div class="row">
        <div class="col-4 mb-5">
          <div class="col-bg">
            <h4 class="second-font pt-5">Kibble</h4>
            <p>Dry dog food</p>
            <img class="w-75" src="../assets/img/food-transparent-18-400x420.png" alt="food">
            <button class="btn btn-success rounded-pill mb-5">Shop dry food</button>
          </div>
        </div>
        <div class="col-4">
          <div class="col-bg mb-5">
            <h4 class="pt-5 second-font">Moist</h4>
            <p>Canned dog food</p>
            <img class="w-75" src="../assets/img/food-transparent-17-400x420.png" alt="food">
            <button class="btn btn-success rounded-pill mb-5">Shop moist food</button>
          </div>
        </div>
        <div class="col-4">
          <div class="col-bg mb-5">
            <h4 class=" second-font pt-5">Frozen</h4>
            <p>Freeze-Dried dog food</p>
            <img class="w-75" src="../assets/img/food-transparent-16-400x420.png" alt="food">
            <button class="btn btn-success rounded-pill mb-5">Shop Frozen food</button>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- Food Shop section -->
</template>

<script>
export default {
  name: "FirstSection",
}
</script>

<style lang="scss" scoped>
@import "../style/common.scss";
.shop-category {
  width: 100%;
  padding-top: 15%;
} 
.col-bg {
  background-color: $secondary-color;
  background-image: url(../assets/img/bg-transparent-3.png);
  color: white;
}
</style>