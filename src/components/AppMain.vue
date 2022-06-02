<template>
  <div>
    <div id="shop-list">
      <AppProduct 
      v-for="(item,index) in products"
      :key="index"
      :productObj="item"/>
    </div>

    <main>
      <div class="jumbotrom-container">
        <AppJumbotrom />  
      </div>

      <FirstSection class="pb-5"/>

      <SecondSection />

      <ThirdSection />

      <FourthSection />

      <FifthSection />
    </main>
  </div>
</template>

<script>
import AppProduct from "../components/AppProduct.vue";
import AppJumbotrom from "../components/AppJumbotrom.vue";
import FirstSection from "../components/FirstSection.vue";
import SecondSection from "../components/SecondSection.vue";
import ThirdSection from "../components/ThirdSection.vue";
import FourthSection from "../components/FourthSection.vue";
import FifthSection from "../components/FifthSection.vue";
export default {
  name: "AppMain",
  components: {
    AppProduct,
    AppJumbotrom,
    FirstSection,
    SecondSection,
    ThirdSection,
    FourthSection,
    FifthSection,
  },
  data() {
      return {
      products: [
          {
          "name": "Pet Ball",
          "produced": "May 9th,2019",
          "category": "Toys",
          "price": "$9.99",
          "image": "2",
          },
          {
          "name": "Dog Bone",
          "produced": "March 9th,2022",
          "category": "Food",
          "price": "$9.99",
          "image": "3",
          },
          {
          "name": "Dog Bag",
          "produced": "September 30th,2020",
          "category": "Transport",
          "price": "$39.99",
          "image": "4",
          },
          {
          "name": "Dog Transport cage",
          "produced": "May 9th,2019",
          "category": "Transport",
          "price": "$49.99",
          "image": "5",
          },
            {
          "name": "Pet Bed green",
          "produced": "Jannuary 17th,2022",
          "category": "Bed",
          "price": "$19.99",
          "image": "8",
          },
          {
          "name": "Pet Bed",
          "produced": "Jannuary 17th,2022",
          "category": "Bed",
          "price": "$19.99",
          "image": "9",
          },
          {
          "name": "Cat Bag",
          "produced": "May 9th,2019",
          "category": "Transport",
          "price": "$29.99",
          "image": "10",
          },
          {
          "name": "Dog leash",
          "produced": "April 29th,2020",
          "category": "Transport",
          "price": "$7.99",
          "image": "11",
          },
          {
          "name": "Cat transport cage ",
          "produced": "May 9th,2019",
          "category": "Transport",
          "price": "$39.99",
          "image": "16",
          },
          {
          "name": "Dog leash pink",
          "produced": "April 29th,2020",
          "category": "Transport",
          "price": "$7.99",
          "image": "20",
          },
           {
          "name": "Transport cage",
          "produced": "May 9th,2019",
          "category": "Transport",
          "price": "$25.99",
          "image": "21",
          }
        ],
    }
  },
};
</script>

<style scoped lang="scss">
@import "../style/common.scss";
#shop-list {
  display: none; //Debug
  //display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  max-width: 80%;
  margin: 0 auto;
  margin-top: 30px
}
.jumbotrom-container { 
  background-color: $secondary-color;
  background-image: url(../assets/img/bg-transparent-3.png);
  background-size: unset;
  height: 100vh;
  padding-top: 120px;
}
</style>
