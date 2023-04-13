<script>
export default {
  data() {
    return {

    }
  }
} 
</script>

<template class="debug">
  <header></header>
  <main></main>
  <footer>
    <div class="footer_top"></div>
    <div class="footer_bottom"></div>
  </footer>
</template>

<style lang="scss">
.debug {
  header {
    height: 122px;
    background-color: b1b2b5;
  }

  main {
    height: 129px;
    background-color: 7e2b97;
  }

  footer {
    .footer_top {
      height: 365px;
      background-color: 3a59b8;
    }

    .footer_bottom {
      height: 103px;
      background-color: 841a56;
    }
  }

}
</style>
