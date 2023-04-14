<template>
    <div>
        <swiper :slides-per-view="1" :space-between="50">
            <swiper-slide class="slide-first intro__slide intro__slide--first">
                <img
                    class="intro__slide--bg"
                    src="@/assets/img/intro-slide-1.png"
                    alt=""
                />

                <div class="intro__slide--content">
                    <div class="intro__slide--text"
                        >ПРОИЗВОДСТВО МАЛЯРНОГО ИНСТРУМЕНТАС 2013 года</div
                    >
                    <div class="intro__slide--button">Подробнее</div>
                </div>
            </swiper-slide>
            <swiper-slide class="intro__slide">Slide 2</swiper-slide>
            <swiper-slide class="intro__slide">Slide 3</swiper-slide>
        </swiper>
    </div>
</template>

<script setup>
import { Swiper, SwiperSlide } from "swiper/vue";
import "swiper/css";
</script>
<style lang="sass" scoped>
.intro
    &__slide
        display: flex
        align-items: flex-start
        position: relative
        min-height: 800px

        &--first
            padding: 60px 10px 60px 120px

        &--bg
            position: absolute
            left: 0
            top: 0
            bottom: 0
            right: 0
            max-width: 100%
            width: 100%
            z-index: -1

        &--content
            display: flex
            flex-direction: column
            padding: 70px 50px 20px 50px
            background-color: #9C9C9C
            background-color: rgba(0,0 ,0 ,0.3 )
            max-width:460px

        &--text
            text-transform: uppercase
            color: $color-white
            +intMed()
            font-size: 40px
            margin-bottom: 80px

        &--button
            width: 100%
            display: flex
            justify-content: center
            font-size: 20px
            color:$color-white
            padding: 8px 20px
            border: 1px solid #FFFFFF
</style>
