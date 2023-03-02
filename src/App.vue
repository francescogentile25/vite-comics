
<script>
import HeaderComponent from './components/HeaderComponent.vue';
import MainComponent from './components/MainComponent.vue';
import FooterComponent from './components/FooterComponent.vue';

export default {
  components: {
    HeaderComponent,
    MainComponent,
    FooterComponent,
  },
  data() {
    return {
    }
  },
  methods: {

  },

}
</script>

<template>
  <header>
    <HeaderComponent></HeaderComponent>
  </header>
  <main>
    <MainComponent></MainComponent>
  </main>
  <footer>
    <FooterComponent></FooterComponent>
  </footer>
</template>

<style  lang="scss" scoped>
@use 'styles/partials/generic' as*;


main {
  background-color: black;
  margin-top: 20px
}
</style>
