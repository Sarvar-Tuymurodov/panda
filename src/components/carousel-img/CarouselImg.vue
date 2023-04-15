<template>
    <swiper
        :slides-per-view="1"
        :space-between="0"
        :autoplay="{
            delay: 1000,
            disableOnInteraction: false,
        }"
        :modules="modules"
        class="carousel"
    >
        :src="'src/assets/img/carousel-' + index + '.png'"
        <swiper-slide v-for="index in 10" :key="index" class="carousel__slide">
            <img class="carousel__slide--bg" :src="renderSrc(index)" alt="" />
        </swiper-slide>
    </swiper>
</template>

<script setup>
// Import Swiper style
import { Swiper, SwiperSlide } from "swiper/vue";
import { Autoplay } from "swiper";

import "swiper/css";

// import required modules

const modules = [Autoplay];

const renderSrc = (index) => {
    console.log("index", index);
    const str = "/img/carousel-" + index + ".png";

    console.log("src", str);

    return str;
};
</script>

<style lang="sass">
.carousel
    margin-top: 40px

    &__slide
        max-width: 100%
        width: 100%

        display: flex
        justify-content: center

        &--bg
            max-width: 1600px
</style>
