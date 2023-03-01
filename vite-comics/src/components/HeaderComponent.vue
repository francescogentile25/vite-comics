@use './styles/partials/generic' as*;

<template>
    <div class="bg-red">
        <img src="/img/dc-logo.png" alt="">
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Expedita natus eum est nihil! Accusamus incidunt
            corrupti molestiae laborum ut quod, beatae numquam esse commodi? Aut corporis at consequuntur voluptate!
        </p>
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
.bg-red {
    background-color: red;
}

img {
    width: 100px;
}
</style>