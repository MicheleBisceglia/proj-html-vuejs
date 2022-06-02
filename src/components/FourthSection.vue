<template>
  <section class="shop-category text-center mt-5">
    <h2 class="text-center pt-5">Get the best tips & tricks</h2>
    <p class="w-50 mx-auto pb-5">Recent articles</p>
    <div class="container">
      <div class="row pb-5">
        <div class="col-3">
          <img class="w-100" src="../assets/img/blog-1-400x400.jpg" alt="">
          <p class="w-75 mx-auto pt-3">How to ‘loose leash walk’ your dog</p>
          <small>April 21st, 2020</small>
        </div>
        <div class="col-3">
          <img class="w-100" src="../assets/img/blog-2-400x400.jpg" alt="">
          <p class="w-75 mx-auto pt-3">Stop cats from scratching furniture</p>
          <small>April 19th, 2020</small>
        </div>
        <div class="col-3">
          <img class="w-100" src="../assets/img/blog-3-400x400.jpg" alt="">
          <p class="w-75 mx-auto pt-3">Where to buy the best pet food</p>
          <small>April 18th, 2020</small>
        </div>
        <div class="col-3">
          <img class="w-100" src="../assets/img/blog-4-400x400.jpg" alt="">
          <p class="w-75 mx-auto pt-3">Proper care for your pet toys</p>
          <small>April 17th, 2020</small>
        </div>
      </div>
    </div>
    <button class="btn btn-success rounded-pill mt-4 mb-5">Read all articles</button>

    <div>
      <div class="d-flex pt-5">
        <div class="position-relative">
          <img class="w-100" src="../assets/img/banner-8-2x.jpg" alt="banner">
          <div class="banner_text">
            <small>FIND THE BEST SUPPLIES</small>
            <h3>Popular accessories</h3>
            <button class="btn btn-light rounded-pill mt-4 mb-5">View all toys accessories</button>
          </div>
        </div>
        <div class="position-relative">
          <img class="w-100" src="../assets/img/banner-9-2x.jpg" alt="banner">
          <div class="banner_text">
            <small>FIND THE BEST SUPPLIES</small>
            <h3>Popular accessories</h3>
            <button class="btn btn-light rounded-pill mt-4 mb-5">View all toys accessories</button>
          </div>
        </div>
      </div>
      
      <div class="my_container pt-5 pb-5">
        <div class="container">
          <div class="row">
            <div class="col-3">
              <i class="fas fa-truck pt-5 pb-5"></i>
              <p>Free worldwide deliveries</p>
            </div>
            <div class="col-3">
              <i class="fas fa-map pt-5 pb-5"></i>
              <p>Find stores near you</p>
            </div>
            <div class="col-3">
              <i class="fas fa-dollar-sign pt-5 pb-5"></i>
              <p>Best prices guarranteed</p>
            </div>
            <div class="col-3">
              <i class="fas fa-credit-card pt-5 pb-5"></i>
              <p>All credit card accepted</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "FourthSection",
}
</script>

<style lang="scss" scoped>
@import "../style/common.scss";
.shop-category {
  width: 100%;
  padding-top: 200px;
} 

.my_container {
  color: white;
  background-color: $secondary-color;
  background-image: url(../assets/img/bg-transparent-3.png);
  i {
    font-size: 3rem;
  }
}

.banner_text {
  position: absolute;
  top: 100px;
  left: 150px;
  color: white;
}
</style>