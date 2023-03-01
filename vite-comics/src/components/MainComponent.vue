<template>
    <div class="container">
        <p class="text">component goes here</p>
        <img src="/img/jumbotron.jpg" alt="" class="jumbo">
    </div>
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

.jumbo {
    max-width: 500px;
    text-align: center;
}

p {
    color: white;
    text-align: center;
}
</style>