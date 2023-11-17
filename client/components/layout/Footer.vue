<template functional>
    <footer class="footer section__footer">
        <div class="footer__content">
            <div class="footer__left">
                <span>Copyright &copy; Abdullah Waseem</span>
            </div>
            <div class="footer__right">
                <span>Github</span>
                <a
                    href="https://github.com/abdullahwaseem01/chat-application"
                    target="_blank"
                    class="nav__link"
                >
                    <ion-icon name="logo-github" class="footer__icon"></ion-icon>
                </a>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'Footer'
};
</script>

<style lang="scss">
@import '@/assets/scss/components/footer.scss';
</style>
