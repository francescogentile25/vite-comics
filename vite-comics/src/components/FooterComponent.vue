<template>
    <header>
        <div class="container">
            <ul class="prova">
                <li class="nav-item">
                    <img src="/img/buy-comics-digital-comics.png" class="icon" alt="">
                    <p class="icon-txt">Digital comics</p>
                </li>
                <li class="nav-item">
                    <img src="/img/buy-comics-merchandise.png" class="icon" alt="">
                    <p class="icon-txt">DC merchandise</p>
                </li>
                <li class="nav-item">
                    <img src="/img/buy-comics-subscriptions.png" class="icon" alt="">
                    <p class="icon-txt">Subscription</p>
                </li>
                <li class="nav-item">
                    <img src="/img/buy-comics-shop-locator.png" class="icon" alt="">
                    <p class="icon-txt">Comic Shop Locator</p>
                </li>
                <li class="nav-item">
                    <img src="/img/buy-comics-digital-comics.png" class="icon" alt="">
                    <p class="icon-txt">Dc pover visa</p>
                </li>
            </ul>
        </div>
    </header>
    <main>
        <div class="container">
            <div class="row">
                <div class="nav-link">
                    <div class="col">
                        <h3>DC COMICS</h3>
                        <ul>
                            <li>lorem</li>
                            <li>lorem</li>
                            <li>lorem</li>
                            <li>lorem</li>
                            <li>lorem</li>
                            <li>lorem</li>
                            <li>lorem</li>
                        </ul>
                    </div>
                    <div class="col">
                        <h3>Shop</h3>
                        <ul>
                            <li>lorem</li>
                            <li>lorem</li>
                        </ul>
                    </div>
                    <div class="col">
                        <h3>DC</h3>
                        <ul>
                            <li>lorem</li>
                            <li>lorem</li>
                            <li>lorem</li>
                            <li>lorem</li>
                            <li>lorem</li>
                            <li>lorem</li>
                            <li>lorem</li>
                            <li>lorem</li>
                            <li>lorem</li>
                            <li>lorem</li>
                            <li>lorem</li>
                        </ul>
                    </div>
                    <div class="col">
                        <h3>Site</h3>
                        <ul>
                            <li>lorem</li>
                            <li>lorem</li>
                            <li>lorem</li>
                            <li>lorem</li>
                            <li>lorem</li>
                        </ul>
                    </div>
                </div>
                <img src="../../public/img/dc-logo-bg.png" class="logo" alt="">
            </div>
        </div>
    </main>
    <footer>
        <div class="container">
            <div class="row">
                <div class="button">
                    <a href="" class="subscribe">Sign up now</a>
                </div>
                <div class="social-logo">
                    <p class="social-title">Follow us</p>
                    <img src="../../public/img/footer-facebook.png" alt="">
                    <img src="../../public/img/footer-twitter.png" alt="">
                    <img src="../../public/img/footer-youtube.png" alt="">
                    <img src="../../public/img/footer-pinterest.png" alt="">
                    <img src="../../public/img/footer-periscope.png" alt="">
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    data() {
        return {
            saluto: 'ciao'
        }
    },
}
</script>

<style lang="scss" scoped>
@use '../styles/partials/generic' as*;
@use '../styles/partials/variables' as*;

.nav-item {
    align-items: center;
    display: flex;
}

.icon {
    width: 42px;
    margin-right: 16px;
}

.icon-txt {
    color: white;
    text-transform: uppercase;
}

header {
    background-color: $blue;
}

.prova {
    padding: 48px;
    justify-content: space-between;
    display: flex;
    gap: 50px;
}

.nav-link {
    color: white;
    display: flex;
    gap: 56px;
}

main {
    overflow: hidden;
    background-image: url(../../public/img/footer-bg.jpg);
}

footer {
    background-color: $grey;
    padding: 30px 0;
}

.row {
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.social-logo {
    display: flex;
    gap: 25px;
    align-items: center;
}

.logo {
    margin-top: -120px;
}

.social-title {
    font-weight: bold;
    text-transform: uppercase;
    color: $blue;
}

.button {
    text-transform: uppercase;
    padding: 15px;
    border: 1px solid $blue;
}
</style>