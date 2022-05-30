<template>
  <div>
    <main>
      <AppProduct />
      <AppProduct />
      <AppProduct />
      <AppProduct />
      <AppProduct />
      <AppProduct />
    </main>
  </div>
</template>

<script>
import AppProduct from "../components/AppProduct.vue";
export default {
  name: "AppMain",
  components: {
    AppProduct,
  }
};
</script>

<style scoped lang="scss">
@import "../style/common.scss";
main {
  background-color: pink;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  max-width: 80%;
  margin: 0 auto;
  margin-top: 30px
}
</style>
