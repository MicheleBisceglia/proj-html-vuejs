<template>
  <div>
     <small class="pt-5">{{ footerListObj.item }}</small>
  </div>
</template>

<script>
export default {
  name: "FooterList2",
  props: {
  footerListObj: Object,
}
}
</script>

<style lang="scss" scoped>
@import "../style/common.scss";
</style>