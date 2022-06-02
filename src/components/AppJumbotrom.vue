<template>
  <div>
    <div class="jumbotrom-top">
      <div class="container">
        <div class="row">
          <div class="col-4 justify-content-center">
            <i class="fas fa-map text-light mx-2"></i>
            <span class="jumbotrom-top-item">Internjational shipping Service</span>
          </div>
          <div class="col-4">
            <i class="fas fa-clock text-light mx-2"></i>
            <span class="jumbotrom-top-item">See our store hours and services</span>
          </div>
          <div class="col-4">
            <i class="fas fa-check text-light mx-2"></i>
            <span class="jumbotrom-top-item">We price match to give you the best deals</span>
          </div>
        </div>
      </div>
        
        
        
      </div>
      <div class="jumbotrom">
        <div class="jumbotrom-center">
          <span class="second-font">FIND THE BEST ANIMAL SUPPLIES</span>
          <h1 class="second-font my-4">We know animals are a part of you family,let us part of your family, let us help take care of them</h1>
          <a href="https://themeforest.net/item/avada-responsive-multipurpose-theme/2833226?irgwc=1&clickid=V21RBCXzJxyIUnxSIMxN7w-dUkDxcIVecQCRTc0&iradid=275988&irpid=1292887&iradtype=ONLINE_TRACKING_LINK&irmptype=mediapartner&mp_value1=&utm_campaign=af_impact_radius_1292887&utm_medium=affiliate&utm_source=impact_radius">Learn more about us</a>
        </div>
      <div class="jumbotrom-bottom">
        <img src="../assets/img/food-transparent-5-400x223.png" alt="">
        <span>Get $25 OFF your first purchase of our homemade pet food!</span>
        <a class="opacity-50" href="">Visit the shop</a>
      </div>
      </div>
  </div>
</template>

<script>
export default {
  name: "AppJumbotrom",
}
</script>

<style lang="scss" scoped>
@import "../style/common.scss";
.jumbotrom-top {
  height: 60px;
  width: 80%;
  margin: 0 auto;
  display: flex;
  align-items: center;
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
.jumbotrom-top-item {
  text-align: center;
  color: white;
  font-size: 80%;
}
.jumbotrom {
  height: 75%;
  background-image: url(../assets/img/banner-5-2x-scaled.jpg);
  background-size: cover;
}
.jumbotrom-center {
  padding-left: 10%;
  padding-top: 10%;
  color: white;
  max-width: 50%;
  & a {
    color: black;
    text-decoration: none;
    background-color: $primary-color;
    padding: 2% 4% 2% 4%;
    border-radius: 30px;
    font-size: 70%;
  }
 }
.jumbotrom-bottom {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 15%;
  color: white;
  background-color: $secondary-color;
  background-image: url(../assets/img/bg-transparent-3.png);
  img {
    height: 100px;
    margin-right: 20px;
  }
  a {
    color: white;
    margin-left: 20px;
  }
 }
</style>