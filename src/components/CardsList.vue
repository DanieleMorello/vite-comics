<script>
import AppCard from './AppCard';
import cards from '../data/cards.js';
export default {
  components: {
    Product
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


    <div class="row row-cols-1 row-cols-sm-2 row-cols-md-4 g-4">

      <Product v-for="card in cards" :image="card.src" :title="card.titolo" />

    </div>
  </section>
</template>

<style lang="scss"></style>