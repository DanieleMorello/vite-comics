<script>
import AppJumbotron from './AppJumbotron.vue';
import CardsList from './CardsList.vue'
export default {
  components: {
    AppJumbotron,
    CardsList
  },
  data() {
    return {

    }
  }
}
</script>

<template>
  <main class="d-flex">
    <AppJumbotron></AppJumbotron>
    <CardsList></CardsList>
  </main>
</template>

<style lang="scss" scoped>
main {
  justify-content: space-around;
  background-color: #000000;
  color: #ffffff;
  padding: 1.5rem;

  p {
    display: flex;
    justify-content: space-around;
    align-items: center;
  }
}
</style>