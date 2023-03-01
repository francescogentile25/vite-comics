
<template>
    <div class="container header">
        <img src="/img/dc-logo.png" alt="">
        <ul class="nav-header">
            <li>
                <a class="nav-item active" href="#">Characters</a>
            </li>
            <li>
                <a class="nav-item" href="#">Comics</a>
            </li>
            <li>
                <a class="nav-item" href="#">Movies</a>
            </li>
            <li><a class="nav-item" href="#"> Tv</a>
            </li>
            <li>
                <a class="nav-item" href="#">Games</a>
            </li>
            <li>
                <a class="nav-item" href="#">
                    Cobles</a>
            </li>
            <li>
                <a class="nav-item" href="#">Videos</a>
            </li>
            <li>
                <a class="nav-item" href="#">Fans</a>
            </li>
            <li>
                <a class="nav-item" href="#">News</a>
            </li>
            <li>
                <a class="nav-item" href="#">Shop</a>
            </li>
        </ul>
    </div>
</template>

<!-- <script>
    export default {
        data() {
            return {
                saluto: 'ciao'
            }
        },
    }
</script> -->

<style lang="scss" scoped>
@use '../styles/partials/generic' as*;

.header {
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.nav-header {
    display: flex;
    gap: 34px;
}

.nav-item {
    padding: 51px 0;
}

.active {
    color: blue;
    border-bottom: 2px solid blue;
}
</style>