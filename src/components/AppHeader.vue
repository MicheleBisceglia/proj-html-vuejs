<template>
  <div>
    <header>
      <div class="header_top">
        <div class="header_top_item">
          <img src="../assets/img/dark-pet-logo.png" alt="">
        </div>
        <div class="header_top_item">
          <input type="text" placeholder="search">
        </div>
        <div class="header_top_item contacts">
          <strong>Questions? </strong>
          <span>call us : 1.8000.123.4567</span>
        </div>
        <div class="header_top_item">
          <i class="fas fa-user"></i>
          <i class="fab fa-shopify"></i>
        </div>
      </div>
      <div class="header_btm">
        <ul>
          <li>
            <span>Home</span>
            <i class="fas fa-angle-down"></i>
            </li>
          <li><span>Shop</span>
            <i class="fas fa-angle-down"></i></li>
          <li>
            <span>About</span>
          </li>
          <li>
            <span>Blog</span>
          </li>
          <li>
            <span>Contact</span>
          </li>
          <li>
            <span>Shop by brand</span>
            <i class="fas fa-angle-down"></i>
          </li>
        </ul>
      </div>
    </header>
  </div>
</template>

<script>
export default {
  name: "AppHeader",
};
</script>

<style scoped lang="scss">
@import "../style/common.scss";
.header_top {
  height: 60px;
  background-color: $primary-color;
  border-bottom: 1px solid $light-color;
  display: flex;
  justify-content: center;
  align-items: center;
  .header_top_item {
    min-width: 20%;
    height: 70%;
    display: flex;
    justify-content: center;
    align-items: center;
    img {
      height: 90%;
      width: 90%;
  }
  input {
      background-color: $light-color;
      border-style: none;
      border-radius: 20px;
      height: 30px;
      width: 90%;
      padding-left: 30px;
    }
  i {
    margin-left: 10px;
  }
  }
  .contacts {
    font-size: 90%;
    background-color: $light-color;
    display: flex;
    border-radius: 20px;
    height: 30px;
    align-items: center;
    justify-content: center;
  }
}
.header_btm {
  height: 50px;
  width: 100%;
  background-color: $primary-color;
  display: flex;
  justify-content: center;
  align-items: center;
  li {
  display: inline;
  padding-left: 20px;
  font-size: 80%;
  opacity: 60%;
  }
  i {
    margin-left: 5px
  }
}

</style>
