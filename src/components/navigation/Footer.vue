<template>
    <footer class="footer">
        <div class="container">
            <div class="footer__body">
                <div class="footer__copyright">Все права защищены</div>
                <div class="footer__social">
                    <a href=""><img src="@/assets/img/fa-social.svg" alt="" /></a>
                    <a href=""><img src="@/assets/img/yt-social.svg" alt="" /></a>
                    <a href=""><img src="@/assets/img/ins-social.svg" alt="" /></a>
                    <a href=""><img src="@/assets/img/tg-social.svg" alt="" /></a>
                </div>
                <div class="footer__date">2013-2023</div>
            </div>
        </div>
    </footer>
</template>
<style lang="sass">
.footer
    padding: 30px 0
    background-color: #1A1A1A

    &__body
        display: flex
        justify-content: space-between

    &__copyright
        font-size: 20px
        +intSemiBold()
        color: $color-white

    &__social
        display: flex

        a:not(:last-child)
            margin-right: 10px

    &__date
        font-size: 20px
        color:$color-white
        +intSemiBold()
</style>
