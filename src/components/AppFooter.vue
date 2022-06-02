<template>
  <div>
    <footer class="text-center text-white">
  <!-- Grid container -->
  <div class="container pt-4">
     <section class="footer_top pb-4">
    <div class="container text-center text-md-start mt-5">
      <div class="row mt-3">
        <div class="col-md-3 col-lg-4 col-xl-3 mx-auto mb-4">
          <div class="mb-4 mt-5">
            <img src="../assets/img/mobile-light-pet-logo-2x-200x52.png" alt="logo">
          </div>
           <FooterInfo 
            v-for="(item, index) in information"
            :key="index"
            :infoObj="item"/>
      </div>

        <div class="col-md-2 col-lg-2 col-xl-2 mx-auto mb-4">
          <!-- Links -->
          <h6 class="mb-4 mt-5">
            Shop by brand
          </h6>
          <FooterList 
            v-for="(item, index) in list1"
            :key="index"
            :footerListObj="item"/>
        </div>
      
        <div class="col-md-3 col-lg-2 col-xl-2 mx-auto mb-4">
          <h6 class="second-font fw-bold mb-4 mt-5">
            Useful links
          </h6>
          <FooterList2
            v-for="(item, index) in list2"
            :key="index"
            :footerListObj="item"/>
        </div>
        <div class="col-md-4 col-lg-3 col-xl-3 mx-auto mb-md-0 mb-4 bg-container">
          <div>
            <h5 class="second-font mt-5 mb-3">Subscrime to our newsletter</h5>
            <div>
              <input class="w-100 p-2 mb-2" type="text" placeholder="insert your email ...*">
            </div>
            <div>
              <button class="w-100 btn btn-success rounded-pill mb-1 p-2">Subscibe</button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

    <!-- Section: Social media -->
    <section class="mb-5 mt-5">
      <ul class="footer_list mb-4">
        <FooterMenu 
          v-for="(item, index) in footerMenu"
          :key="index"
          :footerListObj="item"/>
      </ul>
      <!-- Facebook -->
      
        <FooterIcon
        v-for="(item, index) in icons"
          :key="index"
          :footerListObj="item"/>
     
    </section>
    <!-- Section: Social media -->
  </div>
  <!-- Grid container -->

   <!-- Copyright -->
  <div class="footer_btm text-center p-3">
      © Copyright 2012 - 2022 | Avada Theme by ThemeFusion | All Rights Reserved | Powered by WordPress
  </div>
  <!-- Copyright -->
</footer>
  </div>
</template>

<script>
import FooterInfo from "../components/FooterInfo.vue";
import FooterList from "../components/FooterList.vue";
import FooterList2 from "../components/FooterList2.vue";
import FooterMenu from "../components/FooterMenu.vue";
import FooterIcon from "../components/FooterIcon.vue"
export default {
  name: "AppFooter",
  components: {
   FooterInfo,
   FooterList,
   FooterList2,
   FooterMenu,
   FooterIcon
  },
  data() {
    return {
      props: {
      infoObj: Object,
      footerListObj: Object,
    },
    //Lista informazioni footer
      information: [
        {
          info: "1234 Avada Avenue Avadaville",
        },
        { 
          info: "info@your-company.com",
        },
        {
          info: "Call us: (1) 234 5678"
        }
      ],

      //Lista footer 1
      list1: [
        {
          item: "Bed",
        },
        {
          item: "Food",
        },
        {
          item: "Toys",
        },
        {
          item: "Transort",
        },
      ],

      //Lista footer 2
      list2: [
        {
          item: "My account",
        },
        {
          item: "Orders",
        },
        {
          item: "Checkout",
        },
        {
          item: "Cart",
        },
      ],

      //menu footer
      footerMenu: [
        {
          item: "Home",
        },
        {
          item: "About",
        },
        {
          item: "Blog",
        },
        {
          item: "Contact",
        },
        {
          item: "Shop"
        }
      ],

      //social footer
      icons: [
        {
          item: "fab fa-facebook-f"
        },
        {
          item: "fab fa-twitter"
        },
        {
          item: "fab fa-instagram"
        },
        {
          item: "fab fa-youtube"
        },
      ]
    };
  },
};
</script>

<style scoped lang="scss">
@import "../style/common.scss";
footer {
  background-color: $secondary-color;
}
.footer_top {
  border-bottom: 1px solid $light-color;
}
.footer_btm {
  background-color: black;
}
.footer_list {
  list-style: none;
  display: flex;
  justify-content: center;
  justify-content: space-around;
  max-width: 40%;
  margin: 0 auto;
}
i {
  color:white
}
.bg-container {
  background-image: url(../assets/img/bg-transparent-3.png);
  background-size: cover;
  border: 1px solid $light-color;
  border-radius: 10px;
}
input {
  background-color: $light-color;
  border-style: none;
  border-radius: 20px;
}
</style>
