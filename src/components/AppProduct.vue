<template>
  <div 
    class="product-card">
    <img class="img" :src="require(`../assets/img/product-${productObj.image}-600x600.jpg`)" alt="">
    <h4 class="center">{{ productObj.name }}</h4>
    <p class="center">{{ productObj.produced }}</p>
  </div>
</template>

<script>
export default {
  props: {
    productObj: Object
  },
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