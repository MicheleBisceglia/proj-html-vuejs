<template>
  <div>
    <header>
      <div class="header_top pt-3 pb-3">
        
        <HeaderItem 
        v-for="(item, index) in headerItem"
        :key="index"
        :itemObj="item"/>
        
            
          
      </div>
      <div class="header_btm size_60">
        <HeaderList 
        v-for="(item, index) in headerList"
        :key="index"
        :listObj="item"/>
      </div>
    </header>
  </div>
</template>

<script>
import HeaderList from "../components/HeaderList.vue";
import HeaderItem from "../components/HeaderItem.vue";
export default {
  name: "AppHeader",
  components: {
    HeaderItem,
    HeaderList,
  },
  data() {
    return {
      props: {
      listObj: Object
    },
      headerItem: [
        {
          logo: "dark-pet-logo.png",
          contact: "1.8000.123.4567",
        },
      ],
      headerList: [
        {
          list: "Home",
        },
        {
          list: "Shop",
        },
        {
          list: "About",
        },
        {
          list: "Blog",
        },
        {
          list: "Contact",
        },
        {
          list: "Shop by brand",
        },
      ],
    };
  },
};
</script>

<style scoped lang="scss">
@import "../style/common.scss";
header {
  position: fixed;
  z-index: 99;
  background-color: $primary-color;
  width: 100%;
}
.header_top {
  border-bottom: 2px solid $light-color;
}
.size_60 {
  font-size: 80%;
}
.header_btm {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 50px;
}
</style>
