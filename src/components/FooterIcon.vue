<template>
  <a class="btn-floating btn-lg m-1">
     <i :class="'fab ' + footerListObj.item"></i>
  </a>
</template>

<script>
export default {
  name: "FooterIcon",
  props: {
  footerListObj: Object,
}
}
</script>

<style lang="scss" scoped>
@import "../style/common.scss";
i {
  color: white;
}
</style>