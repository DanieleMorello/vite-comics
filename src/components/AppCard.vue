<script>
export default {
  name: 'AppCard',
  props: {
    thumb: String,
    price: String,
    series: String,
    type: String,
  },
}
</script>
<template>
  <div class="container">
    <div class="row">
      <div class="col">
        <div class="card">
          <img class="img - fluid" :src="thumb" :alt="series">
          <h6>{{ series }}</h6>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.container {



  .card {
    width: 10rem;
    background-color: black;
    padding: .2rem;

    img {
      margin-bottom: 1rem;
      aspect-ratio: 1;
      object-fit: cover;
    }

    h6 {
      text-transform: uppercase;
      color: white;
      font-size: .8rem;
    }
  }

}
</style>