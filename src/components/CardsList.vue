<script>
import AppCard from './AppCard.vue';
import cards from '/data/cards.js';
export default {
  components: {
    AppCard
  },
  data() {
    return {
      cards: cards
    }
  }
}
</script>

<template>
  <section class="container">
    <div class="row row-cols-1 row-cols-sm-4 row-cols-md-6 gx-0">
      <AppCard v-for="card in cards" :thumb="card.thumb" :series="card.series"></AppCard>
    </div>
  </section>
  <div class="text-center">
    <button class="border-0">load more</button>
  </div>
</template>

<style lang="scss" scoped>
div {
  margin-top: .8rem;
}

button {
  background-color: #0282f9;
  margin-top: 1rem;
  color: #ffffff;
  text-transform: uppercase;
  padding: 1rem 3rem;
  border-radius: 2px;
}
</style>