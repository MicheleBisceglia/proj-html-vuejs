<template>
  <div>
    <div class="container">
      <div class="row align-items-center justify-content-center">
        <div class="col-3 text-center">
          <img class="w-75" :src="require(`../assets/img/${itemObj.logo}`)" alt="logo">
        </div>
        <div class="col-3 text-center">
          <div class="my_input ml-3 pt-1 pb-1 lao">
            <i class="fas fa-search"></i>
            <input type="text"
            placeholder="Search...">
          </div>
        </div>
        <div class="col-3 text-center">
          <div class="size_60 text-end">
            <strong>Questions? </strong>
            <span>Call us : {{ itemObj.contact }}</span>
          </div>
        </div>
        <div class="col-3 text-center">
          <i class="fas fa-user px-3"></i>
          <i i class="fab fa-shopify"></i>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeaderItem",
  props: {
  itemObj: Object,
}
};
</script>

<style scoped lang="scss">
@import "../style/common.scss"; 
.my_input {
  background-color: $light-color;
  border-radius: 25px;
  display: flex;
  justify-content: center;
  align-items: center;
  input {
      background-color: $light-color;
      border-style: none;
  }
  i {
   margin-left: 10px;
   margin-right: 20px; 
  }
}
.size_60 {
  font-size: 80%;
}
</style>