<template>
    <div class="home">
        <SwiperIntro />

        <section class="products">
            <div class="container">
                <h3 class="products__title">Каталог Продукции</h3>
                <div class="products__list">
                    <div class="products__item">
                        <div class="products__item--img">
                            <img src="@/assets/img/product-1.png" alt="" />
                        </div>
                        <div class="products__item--text">Валики</div>
                    </div>
                    <div class="products__item">
                        <div class="products__item--img">
                            <img src="@/assets/img/product-2.png" alt="" />
                        </div>
                        <div class="products__item--text">Кисты</div>
                    </div>
                    <div class="products__item">
                        <div class="products__item--img">
                            <img src="@/assets/img/product-3.png" alt="" />
                        </div>
                        <div class="products__item--text">Шпатели</div>
                    </div>
                    <div class="products__item">
                        <div class="products__item--img">
                            <img src="@/assets/img/product-4.png" alt="" />
                        </div>
                        <div class="products__item--text">Cкотчи</div>
                    </div>
                </div>
            </div>
        </section>

        <CarouselImg />

        <section class="goal">
            <div class="container">
                <div class="goal__head">
                    <img src="@/assets/img/since-year.png" alt="" />
                </div>
                <div class="goal__body">
                    <article class="goal__item">
                        <div class="goal__item--top"></div>
                        <div class="goal__item--bottom">
                            <div class="goal__item--img">
                                <img src="@/assets/img/goal-1.png" alt="" />
                            </div>
                            <div class="goal__item--title">Наша цель</div>
                            <div class="goal__item--text"
                                >создание конкурентоспособной продукции с высоким
                                качеством среди ведущих производителей малярных
                                инструментов на ринке.</div
                            >
                        </div>
                    </article>
                    <article class="goal__item">
                        <div class="goal__item--top"></div>
                        <div class="goal__item--bottom">
                            <div class="goal__item--img">
                                <img src="@/assets/img/goal-2.png" alt="" />
                            </div>
                            <div class="goal__item--title">На сегодняшний день</div>
                            <div class="goal__item--text"
                                >большинство строительных и ремонтных площадок уже
                                применяют кисти, валики и шпатели производства.</div
                            >
                        </div>
                    </article>
                    <article class="goal__item">
                        <div class="goal__item--top"></div>
                        <div class="goal__item--bottom">
                            <div class="goal__item--img">
                                <img src="@/assets/img/goal-3.png" alt="" />
                            </div>
                            <div class="goal__item--title"
                                >«PANDA GROUP»
                                <span>преимуществом которых являются:</span></div
                            >
                            <div class="goal__item--text">
                                <li>разновидности инструментов</li>
                                <li> для каждого вида поверхности;</li>
                                <li> максимально удобные ручки </li>
                                <li> для эргономичности </li>
                                <li> выполняемых работ;</li>
                                <li>минимальная подверженность износу</li>
                                <li> продолжительная сохранность исходной формы;</li>
                            </div>
                        </div>
                    </article>
                </div>
            </div>
        </section>

        <section class="partners">
            <div class="container">
                <div class="partners__head">
                    <div class="partners__title">Сотрудничество</div>
                    <div class="partners__subtitle"
                        >Деловые предложения о сотрудничестве</div
                    >
                </div>
                <div class="partners__body">
                    <div class="partners__box">
                        <div class="partners__box--img">
                            <img src="@/assets/img/partners-1.svg" alt="" />
                        </div>

                        <div class="partners__box--content">
                            <div class="partners__box--title">Доставка</div>
                            <div class="partners__box--text"
                                >Мы организуем доставку по всей Узбекистану и странам СНГ.
                                Доставка по Ташкенту осуществляется бесплатно.</div
                            >
                        </div>
                    </div>
                    <div class="partners__box">
                        <div class="partners__box--img">
                            <img src="@/assets/img/partners-2.svg" alt="" />
                        </div>

                        <div class="partners__box--content">
                            <div class="partners__box--title">Доставка</div>
                            <div class="partners__box--text"
                                >Мы организуем доставку по всей Узбекистану и странам СНГ.
                                Доставка по Ташкенту осуществляется бесплатно.</div
                            >
                        </div>
                    </div>
                    <div class="partners__box">
                        <div class="partners__box--img">
                            <img src="@/assets/img/partners-3.svg" alt="" />
                        </div>

                        <div class="partners__box--content">
                            <div class="partners__box--title">Доставка</div>
                            <div class="partners__box--text"
                                >Мы организуем доставку по всей Узбекистану и странам СНГ.
                                Доставка по Ташкенту осуществляется бесплатно.</div
                            >
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="contact">
            <div class="container">
                <div class="contact__head">
                    <div class="contact__title">«PANDA GROUP»</div>
                    <div class="contact__subtitle">Наши контакты</div>
                </div>
                <div class="contact__content">
                    <div class="contact__left">
                        <iframe
                            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d4924.682070968589!2d69.23960277860337!3d41.324820862848384!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x38ae8b77b22cdc43%3A0x5de748623e7d479b!2sToshkent%20Planetarium!5e0!3m2!1sen!2s!4v1681445192295!5m2!1sen!2s"
                            width="700"
                            height="581"
                            style="border: 0"
                            allowfullscreen=""
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade"
                        ></iframe>
                    </div>
                    <div class="contact__right">
                        <div class="contact__row">
                            <div class="contact__row--text">Для звонки</div>
                            <div class="contact__row--box">
                                <img src="@/assets/img/phone-icon.svg" alt="" />
                                <div class="contact__row--box-info">
                                    <a href="tel:+998 97 777 0800">+998 97 777 0800</a>
                                    <a href="tel:++998 97 007 0800">+998 97 007 0800</a>
                                </div>
                            </div>
                        </div>
                        <div class="contact__row">
                            <div class="contact__row--text">Для посещения</div>
                            <div class="contact__row--box">
                                <img src="@/assets/img/geo-icon.svg" alt="" />
                                <div class="contact__row--box-info">
                                    г.Ташкент, Учтепинский район, Строителниый рынок
                                    Урикзор, 5-Блок 9-магазин.
                                </div>
                            </div>
                        </div>
                        <div class="contact__row">
                            <div class="contact__row--text">Для вопросы</div>
                            <div class="contact__row--box">
                                <img src="@/assets/img/tg-icon.svg" alt="" />
                                <div class="contact__row--box-info">
                                    <a href="https://t.me/Umidjon1991">@Umidjon1991</a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<script setup>
import SwiperIntro from "@/components/swiper-intro/SwiperIntro.vue";
import CarouselImg from "@/components/carousel-img/CarouselImg.vue";
</script>

<style lang="sass">
.products
    padding: 60px 0
    background-color: #EBEBEB

    &__title
        text-align: center
        width: 100%
        color:#000
        font-size: 50px
        +intBold()
        margin-bottom: 55px

    &__list
        display: grid
        grid-template-columns: repeat(4,1fr)
        grid-gap:15px

    &__item
        display: flex
        flex-direction: column
        justify-content: space-between
        padding: 50px 15px
        align-items: center
        background-color: $color-white
        border-radius: 40px
        transition: all .2s
        cursor: pointer

        &:hover
            box-shadow: rgba(255, 102, 0, 0.4) 0px 30px 70px -31px

            .products__item--text
                background-color: #000000
                border-radius: 15px
                color: $color-white

        &--img
            margin-bottom: 40px
            display: flex
            align-items: center
            flex-grow: 1

        &--text
            color: #858585
            transition: all .2s
            font-size: 40px
            color: #858585
            width: 80%
            padding: 10px 25px
            text-align: center

.goal
    margin-top: 90px
    margin-bottom: 90px
    &__head
        display: flex
        justify-content: center

        width: 100%

    &__body
        display: flex
        justify-content: space-around

    &__item
        max-width: 440px

        display: flex
        flex-direction: column

        &:last-child
            .goal__item--title
                line-height: 1

                span
                    font-size: 18px
                    +intMed()
                    font-weight: 500
                    line-height: 1

            .goal__item--text
                list-style: circle
                font-size: 18px

                li
                    list-style-type: disc
                    padding: 0 5px

        &--top
            width: 100%
            min-height: 140px
            border-radius: 40px 40px 0 0
            background-color:  #FF6600
            translate:  0 50px

        &--bottom
            display: flex
            flex-direction: column
            flex-grow: 1
            padding: 15px 50px 80px 50px
            border-radius: 40px
            background-color: #150D00
            color: $color-white
            position: relative
            padding-top: 200px

        &--img
            position: absolute
            left: 50%
            top: -40px
            translate: -50% 0
            width: 190px
            height: 190px
            display: flex
            align-items: center
            justify-content: center
            background-color: $color-white
            border-radius: 50%


        &--title
            +intBold()
            font-size:36px
            margin-bottom: 10px

        &--text
            +intThin()
            font-size: 20px
            color: $color-white

.partners
    margin-bottom: 90px
    &__head
        display: flex
        align-items: center
        flex-direction: column
        margin-bottom: 100px

    &__title
        font-size: 90px
        color:#FF6600
        +intExtraBold()
        margin-bottom: 10px

    &__subtitle
        font-size:40px
        color: #000000

    &__body
        display: flex
        justify-content: space-between

    &__box
        display: flex
        padding: 150px 40px
        background-color: #EFEFEF
        border-radius: 38px
        max-width: 500px

        &--img
            min-width: 80px
            margin-right: 15px

        &--title
            color:#FF6600
            font-size: 35px
            +intBold()
            margin-bottom: 10px

        &--text
            font-size: 20px
            color: #8E8F90

.contact
    margin-bottom: 90px

    &__head
        display: flex
        flex-direction: column
        align-items: center
        margin-bottom: 60px

    &__title
        font-size: 68px
        color:#FF6600
        +intBold()

    &__subtitle
        font-size: 40px
        color: #646464

    &__content
        display: flex
        justify-content: space-between

    &__right
        display: flex
        flex-direction: column
        justify-content: space-between

    &__row
        display: flex
        align-items: center
        width: 100%
        width: 700px
        margin-bottom: 40px

        &:not(::last-child)
            margin-bottom: 40px


        &:nth-child(2)
            .contact__row--box-info
                max-width: 185px
                font-size: 14px


        &--text
            color:#FF6600
            font-size:35px
            +intSemiBold()
            margin-right: auto

        &--box
            display: flex
            align-items: start
            justify-content: center
            padding: 50px 60px
            background: #EFEFEF
            border-radius: 20px
            max-width: 335px
            width: 100%


            & img
                margin-right: 10px

                translate: 0 6px

            &-info
                display: flex
                flex-direction: column

                & a
                    font-size: 20px
                    +intSemiBold()
                    color:#000000
</style>
