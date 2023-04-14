<template>
    <nav class="nav">
        <div class="container">
            <div class="nav__content">
                <div class="nav__brand">
                    <img src="@/assets/img/logo.svg" alt="" />
                </div>
                <ul class="nav__menu">
                    <li class="nav__item">
                        <RouterLink to="/" href="" class="nav__link">Главная</RouterLink>
                    </li>
                    <li class="nav__item">
                        <RouterLink to="/" href="" class="nav__link">Каталог</RouterLink>
                    </li>
                    <li class="nav__item">
                        <RouterLink to="/" href="" class="nav__link">Контакты</RouterLink>
                    </li>
                    <li class="nav__item">
                        <RouterLink to="/" href="" class="nav__link"
                            >Информация</RouterLink
                        >
                    </li>
                    <div class="nav__phone">
                        <a href="tel:+998977770800">97 777 08 00</a>
                    </div>
                </ul>
                <div class="nav__lang">
                    <select name="" id="">
                        <option value="Ru">Ru</option>
                        <option value="Uz">Uz</option>
                    </select>
                </div>
                <div class="nav__burger"></div>
            </div>
        </div>
    </nav>
</template>

<style lang="sass">
.nav
    padding: 20px 0
    background-color: #1A1A1A
    box-shadow: 0px 2px 50px rgba(255, 102, 0, 0.5)
    margin-bottom: 40px

    &__content
        display: flex
        align-items: center
        width: 100%


    &__menu
        display: flex
        margin-left: auto
        align-items: center

        & > li
            font-size: 30px
            color: $color-white
            // margin-right: 30px

            & > a
                transition: all .1s

            &:hover
                & a
                    color:#FF6600

        & > li:not(:last-child)
            margin-right: 30px

    &__phone
        display: flex
        margin-right: 10px

        & a
            border-radius: 10px
            padding: 15px 40px
            font-size: 30px
            color: $color-white
            +intMed()
            border: 3px solid #FF6600
            transition: all .2s

            &:hover
                background-color: #FF6600
                color: $color-white
</style>
