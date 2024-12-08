<template>
  <swiper
    :modules="modules"
    :slides-per-view="1"
    speed="1200"
    navigation
    :pagination="{ clickable: true }"
    @swiper="onSwiper"
    @slideChange="onSlideChange"
  >
    <swiper-slide><img class="swiper__img" src="../assets/img/mac.png" alt=""></swiper-slide>
    <swiper-slide><img class="swiper__img" src="../assets/img/iphone.png" alt=""></swiper-slide>
  </swiper>
</template>

<script setup>
// import Swiper core and required modules
import { Navigation, Pagination, A11y } from "swiper/modules";

// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from "swiper/vue";

// Import Swiper styles
import "swiper/css";
import "swiper/css/navigation";
import "swiper/css/pagination";


// Modules array for Swiper configuration
const modules = [Navigation, Pagination, A11y];
</script>
<style lang="scss" scoped>
.swiper-slide{
    display: flex !important;
    justify-content: center;
}
.swiper-button-prev:after,.swiper-button-nex:after {
  font-weight:700 !important ;
  color: black !important;
}
.swiper__img{
    scale: 0.9;
    transition: 1s;
    &:hover{
    transition: 1s;
    scale: 1;
}
}

</style>
