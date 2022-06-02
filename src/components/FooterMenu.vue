<template>
  <div>
     <li>{{ footerListObj.item }}</li>
  </div>
</template>

<script>
export default {
  name: "FooterMenu",
  props: {
  footerListObj: Object,
}
}
</script>

<style lang="scss" scoped>
@import "../style/common.scss";
</style>