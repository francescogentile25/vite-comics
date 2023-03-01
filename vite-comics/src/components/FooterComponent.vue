<template>
    <header>
        <div class="container">
            <ul class="prova">
                <li class="nav-item" v-for="icon in icons">
                    <img :src="icon.url" class="icon" alt="">
                    <p class="icon-txt">{{ icon.label }}</p>
                </li>
            </ul>
        </div>
    </header>
    <main>
        <div class="container">
            <div class="row">
                <div class="nav-link">
                    <div class="col" v-for=" link in links">
                        <h3>{{ link.title }}</h3>
                        <ul v-for=" text in link.text">
                            <li>{{ text }}</li>
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
                    <div v-for="src in socialImg">
                        <img :src="src" alt="">
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    data() {
        return {
            saluto: 'ciao',
            icons: [
                {
                    label: 'Digital comics',
                    url: '/img/buy-comics-digital-comics.png'
                },
                {
                    label: 'DC merchandise',
                    url: '/img/buy-comics-merchandise.png'
                },
                {
                    label: 'Subscription',
                    url: '/img/buy-comics-subscriptions.png'
                }, {
                    label: 'Comic Shop Locator',
                    url: '/img/buy-comics-shop-locator.png'
                }, {
                    label: 'Dc pover visa',
                    url: '/img/buy-comics-digital-comics.png'
                },
            ],
            links: [
                {
                    title: 'DC COMICS',
                    text: ['Characterrs', 'Comics', 'Movies', 'Tv', 'Games', 'Videos', 'News']
                },
                {
                    title: ' SHOP',
                    text: ['Shop Dc', 'Shop Dc Collectibles'],
                },
                {
                    title: ' DC',
                    text: ['Terms of Use', 'Privacy policy', 'Ad Choice', 'Advertising', 'Jobs', 'Subsriptions', 'Talent Workshops', 'CPSC Cerificates', 'Ratings', 'Shop Help', 'Conacts Us']
                },
                {
                    title: ' SITES',
                    text: ['Dc', 'Mad Magazine', 'DC Kids', 'Dc Universe', 'Dc Poer Visa'],
                }
            ],
            socialImg: ['../../public/img/footer-facebook.png', '../../public/img/footer-twitter.png', '../../public/img/footer-youtube.png', '../../public/img/footer-pinterest.png', '../../public/img/footer-periscope.png'],
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