<template>
  <div>
    <header>
      <div class="header_top">
        <div class="header_top_item"></div>
        <div class="header_top_item"></div>
        <div class="header_top_item"></div>
        <div class="header_top_item"></div>
      </div>
      <div class="header_btm">
        <ul>
          <li>ietm</li>
          <li>item</li>
          <li>item</li>
          <li>item</li>
          <li>item</li>
          <li>item</li>
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
  display: flex;
  justify-content: center;
  align-items: center;
  .header_top_item {
    width: 20%;
    height: 70%;
    border: 1px solid black;
    img {
      height: 100%;
      width: 100%;
  }
  }
}
.header_btm {
  height: 60px;
  width: 100%;
  background-color: $primary-color;
  display: flex;
  justify-content: center;
  align-items: center;
}
li {
  display: inline;
  padding-left: 10px;
}
</style>
