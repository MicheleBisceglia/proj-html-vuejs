<template>
 <div>
            <small>{{ infoObj.info }}</small>
          </div>
</template>

<script>
export default {
  name: "FooterInfo",
  props: {
  infoObj: Object,
}
}
</script>

<style lang="scss" scoped>
@import "../style/common.scss";
</style>