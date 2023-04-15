<script>
import AppBanner from "./AppBanner.vue"
export default {
  components: {
    AppBanner
  },
  data() {
    return {

    }
  }
}
</script>
<template>
  <AppBanner></AppBanner>
  <div class="footer_top ">
    <div class="container  p-5">
      <div id="links" class="d-flex">
        <div class="">
          <h4>DC COMICS</h4>
          <ul class="p-0">
            <li><a href="#">Characters</a></li>
            <li><a href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">News</a></li>
          </ul>
          <h4 class="my-4">SHOP</h4>
          <ul class="p-0">
            <li><a href="#">Shop DC</a></li>
            <li><a href="#">Shop DC Collectibles</a></li>
          </ul>
        </div>

        <div>
          <h4 class="mx-5">DC</h4>
          <ul class="px-5">
            <li><a href="#">Terms Of Use</a></li>
            <li><a href="#">Privacy policy (New)</a></li>
            <li><a href="#">Ad Choices</a></li>
            <li><a href="#">Advertising</a></li>
            <li><a href="#">Jobs</a></li>
            <li><a href="#">Subscriptions</a></li>
            <li><a href="#">Talent Workshops</a></li>
            <li><a href="#">CPSC Certificates</a></li>
            <li><a href="#">Ratings</a></li>
            <li><a href="#">Shop Help</a></li>
            <li><a href="#">Contact Us</a></li>
          </ul>
        </div>

        <div class="mx-3">
          <h4>SITES</h4>
          <ul class="p-0">
            <li><a href="#">DC</a></li>
            <li><a href="#">MAD Magazine</a></li>
            <li><a href="#">DC Kids</a></li>
            <li><a href="#">DC Universe</a></li>
            <li><a href="#">DC Power Visa</a></li>
          </ul>
        </div>

      </div>
    </div>
  </div>


  <div class="footer_bottom">

    <div class="container d-flex justify-content-between align-items-center">
      <button>sign-up now</button>
      <div class="d-flex align-items-center">
        <h3 class=" ">follow us</h3>
        <ul class="d-flex align-items-center">
          <li>
            <a href="#"><img src="../assets/img/footer-facebook.png" alt="Facebook"></a>
          </li>
          <li>
            <a href="#"><img src="../assets/img/footer-twitter.png" alt="Twitter"></a>
          </li>
          <li>
            <a href="#"><img src="../assets/img/footer-youtube.png" alt="Youtube"></a>
          </li>
          <li>
            <a href="#"><img src="../assets/img/footer-pinterest.png" alt="Pinterest"></a>
          </li>
          <li>
            <a href="#"><img src="../assets/img/footer-periscope.png" alt="Periscope"></a>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
h4 {
  color: #ffffff;
}

a {
  text-decoration: none;
}

a {
  color: #5d5e64;
}

li {
  list-style: none;

  button {
    color: #5d5e64;
    font-size: .7rem;
  }
}

.footer_top {
  background-image: url("../assets/img/footer-bg.jpg"), url("../assets/img/dc-logo-bg.png");
  background-repeat: no-repeat, no-repeat;
  background-size: cover, auto;
  background-position: center, 65rem;
  background-blend-mode: overlay;
}

.footer_bottom {
  background-color: #303030;

  button {
    border: 2px solid #0e67a1;
    padding: .8rem;
    color: #ffffff;
    background-color: #303030;
    text-transform: uppercase;
  }

  h3 {
    color: #0e67a1;
    text-transform: uppercase;
  }

  li {
    padding: 1rem;
  }
}
</style>