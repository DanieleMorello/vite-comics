<script>
export default {
  data() {
    return {
      activeLink: 0

    }
  },
  methods: {
    setActiveLink(index) {
      console.log(index);
      this.activeLink = index;
      console.log("Link attivo", this.activeLink);
    }
  }
}
</script>

<template>
  <header>
    <div>
      <img src="../assets/img/dc-logo.png" alt="" class="logo">
    </div>
    <ul>
      <li><a href=" #">characters</a></li>
      <li><a href="#">comics</a></li>
      <li><a href="#">movies</a></li>
      <li><a href="#">tv</a></li>
      <li><a href="#">games</a></li>
      <li><a href="#">collectibles</a></li>
      <li><a href="#">videos</a></li>
      <li><a href="#">fans</a></li>
      <li><a href="#">news</a></li>
      <li><a href="#">shop</a></li>
    </ul>
  </header>
</template>

<style lang="scss" scoped>
$text-dark: #000000;

header {
  display: flex;
  justify-content: space-around;
  align-items: center;
  padding: 1rem 0;

  .logo {
    width: 81px;
  }

  ul {
    display: flex;

    li {
      padding: 1rem;
      list-style: none;

      a {
        color: $text-dark;
        text-transform: uppercase;
        font-weight: bold;
        text-decoration: none;
      }
    }
  }
}

.active {
  color: #0282f9;
}
</style>