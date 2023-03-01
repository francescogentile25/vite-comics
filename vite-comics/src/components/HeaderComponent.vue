
<template>
    <div class="container header">
        <img src="/img/dc-logo.png" alt="">
        <ul class="nav-header">
            <li v-for=" text in link">
                <a class="nav-item active" href="#">{{ text }}</a>
            </li>
        </ul>
    </div>
</template>

<script>
export default {
    data() {
        return {
            saluto: 'ciao',
            link: ['Characters', 'Comics', 'Movies', 'Tv', 'Games', 'Collectibles', 'Videos', 'Fans', 'News', 'Shop']
        }
    },
}
</script>

<style lang="scss" scoped>
@use '../styles/partials/generic' as*;
@use '../styles/partials/variables' as*;

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

.active,
.nav-item:hover {
    color: $blue;
    border-bottom: 2px solid $blue;
}
</style>