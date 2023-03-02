<template>
    <div class="card">
        <img :src="card.thumb" alt="" class="card-image">
        <p class="card-title">{{ card.series }}</p>
    </div>
</template>

<script>
export default {
    props: {
        card: {
            type: Object,
            required: true
        },
    },
    data() {
        return {
            saluto: 'ciao',
        }
    },
}
</script>

<style lang="scss" scoped>
@use '../styles/partials/generic' as*;

p {
    color: white;
}
</style>