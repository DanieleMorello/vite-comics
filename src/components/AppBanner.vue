<script>
export default {

  data() {
    return {
      // links: [
      //   {
      //     img: "../assets/img/buy-comics-digital-comics.png",
      //     title: "Digital comics",
      //     link: "#",
      //   },
      //   {
      //     img: "../assets/img/buy-comics-merchandise.png",
      //     title: "DC merchandise",
      //     link: "#",
      //   },
      //   {
      //     img: "../assets/img/buy-comics-subscriptions.png",
      //     title: "Subscription",
      //     link: "#",
      //   },
      //   {
      //     img: "../assets/img/buy-comics-shop-locator.png",
      //     title: "Comic shop locator",
      //     link: "#",
      //   },
      //   {
      //     img: "../assets/img/buy-dc-power-visa.svg",
      //     title: "DC power visa",
      //     link: "#",
      //   },
      // ]
    }
  }
}
</script>
<template>
  <div class="row gx-0">
    <div class="col">
      <div class="banner d-flex justify-content-around align-item-center">
        <div>
          <img src="../assets/img/buy-comics-digital-comics.png" alt="Digital comics">
          <a href="#"> Digital comics</a>
        </div>

        <div>
          <img src="../assets/img/buy-comics-merchandise.png" alt="DC merchandise">
          <a href="#"> DC merchandise</a>
        </div>

        <div>
          <img src="../assets/img/buy-comics-subscriptions.png" alt="Subscription">
          <a href="#"> Subscription</a>
        </div>

        <div>
          <img src="../assets/img/buy-comics-shop-locator.png" alt="Comic shop locator">
          <a href="#"> Comic shop locator</a>
        </div>

        <div>
          <img src="../assets/img/buy-dc-power-visa.svg" alt="DC power visa">
          <a href="#"> DC power visa</a>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.banner {
  background-color: #0282f9;
  color: white;
  padding: 5rem 10rem;

  img {
    height: 50px;
  }

  a {
    text-decoration: none;
    text-transform: uppercase;
    color: #ffffff;
  }

}
</style>