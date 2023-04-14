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


    <div class="d-flex">

      <AppCard v-for="card in cards" :thumb="card.thumb" :series="card.series"></AppCard>

    </div>
  </section>
</template>

<style lang="scss"></style>