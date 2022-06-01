<template>
  <div>
      <div class="header_btm">
        <div class="container">
          <div class="row ">
            <div class="col-12 ">
              <span class="">
                {{ listObj.list }}
              </span>
            </div>
          </div>
        </div>  
      </div>
  </div>
</template>

<script>
export default {
  name: "HeaderList",
  props: {
  listObj: Object,
}
};
</script>

<style scoped lang="scss">
@import "../style/common.scss"; 
</style>