<script>
export default {
  data() {
    return {
      activeLink: 1,
      links: [
        {
          href: '#',
          text: 'characters',

        },
        {
          href: '#',
          text: 'comics',
          active: true,
        },
        {
          href: '#',
          text: 'movies',

        },
        {
          href: '#',
          text: 'tv',

        },
        {
          href: '#',
          text: 'games',

        },
        {
          href: '#',
          text: 'collectibles',

        },
        {
          href: '#',
          text: 'videos',

        },
        {
          href: '#',
          text: 'fans',

        },
        {
          href: '#',
          text: 'news',

        },
        {
          href: '#',
          text: 'shop',

        },

      ]
    }
  },
  methods: {
    setActiveLink(index) {
      // console.log(index);
      this.activeLink = index;
      console.log("Link attivo", this.activeLink);
    }
  }
}
</script>

<template>
  <div class="container">
    <div class="row">
      <div class="col">

        <nav class="navbar navbar-expand-lg navbar-light bg-light fixed-top">
          <div class="container">
            <a class="navbar-brand" href="#">
              <img src="../assets/img/dc-logo.png" alt="" class="logo">
            </a>

            <button class="navbar-toggler hidden-lg-up" type="button" data-bs-toggle="collapse"
              data-bs-target="#collapsibleNavId" aria-controls="collapsibleNavId" aria-expanded="true"
              aria-label="Toggle navigation">
            </button>

            <div class="collapse navbar-collapse" id="collapsibleNavId">
              <ul class="navbar-nav ms-auto mt-2 mt-lg-0">
                <li class="nav-item d-flex ms-auto">
                  <a class="nav-link" :href="link.href" v-for="(link, index) in links"
                    :class="{ active: activeLink === index }">
                    {{ link.text }}
                  </a>
                </li>
              </ul>
            </div>
          </div>
        </nav>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.logo {
  width: 81px;
}

ul {
  display: flex;

  li {
    list-style: none;
  }

}

a {
  $text-dark: #000000;
  color: $text-dark;
  text-transform: uppercase;
  font-weight: bold;
  text-decoration: none;
}

#collapsibleNavId .nav-item a.active {
  color: #0282f9;
  position: relative;
}

a.active::after {
  content: '';
  position: absolute;
  bottom: -35px;
  left: 0;
  width: 100%;
  height: 5px;
  background-color: #0282f9;
}
</style>