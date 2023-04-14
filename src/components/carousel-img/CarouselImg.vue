<template>
    <swiper
        :slides-per-view="1"
        :space-between="0"
        :autoplay="{
            delay: 100000,
            disableOnInteraction: false,
        }"
        :modules="modules"
        class="carousel"
    >
        <swiper-slide class="carousel__slide">
            <img class="carousel__slide--bg" src="@/assets/img/carousel-1.png" alt="" />
        </swiper-slide>
        <swiper-slide class="carousel__slide">
            <img class="carousel__slide--bg" src="@/assets/img/carousel-1.png" alt="" />
        </swiper-slide>
        <swiper-slide class="carousel__slide">
            <img class="carousel__slide--bg" src="@/assets/img/carousel-1.png" alt="" />
        </swiper-slide>
        <swiper-slide class="carousel__slide">Slide 2</swiper-slide>
        <swiper-slide class="carousel__slide">Slide 3</swiper-slide>
    </swiper>
</template>

<script setup>
// Import Swiper style
import { Swiper, SwiperSlide } from "swiper/vue";
import { Autoplay } from "swiper";

import "swiper/css";

// import required modules

const modules = [Autoplay];
</script>

<style lang="sass">
.carousel
    margin-top: 40px

    &__slide
        max-width: 100%
        width: 100%

        display: flex
        justify-content: center
</style>
