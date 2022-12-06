<template>
  <div id="app">
    <div class="container-fluid text-black">
      <div class="row">
        <nav class="navbar navbar-expand-lg bg-light py-3">
          <div class="container-fluid">
            <router-link class="navbar-brand" to="/">
              <button class="btn btn-basic btn-outline-light">
                <img
                  src="./assets/elogo.svg"
                  width="195"
                  alt=""
                  class="img-fluid align-center mr-2"
                />
              </button>
            </router-link>
            <div class="collapse navbar-collapse" id="navbarScroll">
              <ul
                class="navbar-nav mx-auto my-2 my-lg-0 navbar-nav-scroll"
                style="--bs-scroll-height: 100px"
              >
                <li class="nav-item">
                  <router-link class="nav-link active" aria-current="page" to="/">
                    Home
                  </router-link>
                </li>
                <li class="nav-item">
                  <router-link class="nav-link active" aria-current="page" to="/about">
                    About
                  </router-link>
                </li>
                <li class="nav-item">
                  <router-link class="nav-link active" aria-current="page" to="/service">
                    Services
                  </router-link>
                </li>
                <li class="nav-item">
                  <router-link class="nav-link active" aria-current="page" to="/contact">
                    Contact
                  </router-link>
                </li>
              </ul>

              <router-link class="navbar" to="/contact">
                <button class="btn btn-basic btn-outline-light">
                  <img
                    src="./assets/top-m-icon.png"
                    alt=""
                    class="img-fluid align-center mr-2"
                  />
                </button>
              </router-link>
            </div>
          </div>
        </nav>
      </div>

      <router-view />
      <Footer />
    </div>
  </div>
</template>
<script>
import Footer from "./components/Footer.vue";
export default {
  name: "App",
  components: {
    Footer,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>
