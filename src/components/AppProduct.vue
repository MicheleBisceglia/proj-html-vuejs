<template>
  <div class="product-card">
    <div class="img"></div>
    <h4 class="center">Dog leash</h4>
    <p class="center">April 29th, 2020 | Transport</p>
  </div>
</template>

<script>
export default {
  name: "AppProduct"
}
</script>

<style lang="scss" scoped>
  .product-card {
    height: 300px;
    width: 30%;
    margin-bottom: 20px;
  }
  .img {
    height: 80%;
    width: 100%;
    background-color: violet;
  }
  h4 {
    text-align: center;
    padding-top: 20px;
  }
  p {
    text-align: center;
    font-size: 70%;
  }
</style>