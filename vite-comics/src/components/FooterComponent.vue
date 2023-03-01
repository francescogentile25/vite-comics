<template>
    <ul class="prova container">
        <li class="nav-item">
            <img src="/img/buy-comics-digital-comics.png" class="icon" alt="">
            <p class="icon-txt">Digital comics</p>
        </li>
        <li class="nav-item">
            <img src="/img/buy-comics-merchandise.png" class="icon" alt="">
            <p class="icon-txt">Digital comics</p>
        </li>
        <li class="nav-item">
            <img src="/img/buy-comics-subscriptions.png" class="icon" alt="">
            <p class="icon-txt">Digital comics</p>
        </li>
        <li class="nav-item">
            <img src="/img/buy-comics-shop-locator.png" class="icon" alt="">
            <p class="icon-txt">Digital comics</p>
        </li>
        <li class="nav-item">
            <img src="/img/buy-comics-digital-comics.png" class="icon" alt="">
            <p class="icon-txt">Digital comics</p>
        </li>
    </ul>
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

.prova {
    padding: 48px;
    justify-content: space-between;
    display: flex;
    gap: 70px;
    background-color: blue;
}
</style>