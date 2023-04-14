<script>
import AppJumbotron from './AppJumbotron.vue';
export default {
  components: {
    AppJumbotron,
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