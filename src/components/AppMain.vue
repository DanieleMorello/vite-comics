<script>
import CardsList from './CardsList.vue'
export default {
  components: {
    CardsList
  },
  data() {
    return {

    }
  }
}
</script>

<template>
  <main>
    <section class="container">
      <div class="row">
        <div class="col">
          <button>current series</button>
          <CardsList></CardsList>
        </div>
      </div>
    </section>



  </main>
</template>

<style lang="scss" scoped>
main {
  display: flex;
  justify-content: space-around;
  background-color: #000000;
  color: #ffffff;
  padding: 1.5rem;

  .col {
    position: relative;
  }

  button {
    position: absolute;
    top: -45px;
    left: 26px;
    background-color: #0282f9;
    color: #ffffff;
    text-transform: uppercase;
    font-size: large;
    font-weight: bold;
    padding: .5rem 2rem;
    border-radius: 2px;
    border: 0;
  }
}
</style>