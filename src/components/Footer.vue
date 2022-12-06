<template>
  <div class="container-fluid p-5 bg-primary text-black text-right">
    <div class="row">
      <div class="col-sm-4">
        <h3>About Us</h3>
        <p>
          At Earlsdon Limited we believe in providing the highest standard of
          work for our clients with a friendly and reliable approach. Honesty,
          integrity and putting customers first are at the heart of our service.
        </p>
      </div>
      <div class="col-sm-4">
        <h3>Useful Links</h3>
        <router-link class="nav-link" to="/">Home</router-link>
        <br />
        <router-link class="nav-link" to="/about">About</router-link>
        <br />
        <router-link class="nav-link" to="/service">Service</router-link>
        <br />
        <router-link class="nav-link" to="/contact">Contact</router-link>
      </div>
      <div class="col-sm-4">
        <h3>Contact Here</h3>
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="16"
          height="16"
          fill="currentColor"
          class="bi bi-envelope"
          viewBox="0 0 16 16"
        >
          <path
            d="M0 4a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V4Zm2-1a1 1 0 0 0-1 1v.217l7 4.2 7-4.2V4a1 1 0 0 0-1-1H2Zm13 2.383-4.708 2.825L15 11.105V5.383Zm-.034 6.876-5.64-3.471L8 9.583l-1.326-.795-5.64 3.47A1 1 0 0 0 2 13h12a1 1 0 0 0 .966-.741ZM1 11.105l4.708-2.897L1 5.383v5.722Z"
          />
        </svg>
        <br />
        <a href="#" class="btn btn-basic">
          <h6>info@earlsdon.org</h6>
        </a>
        <br />
        <br />
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="16"
          height="16"
          fill="currentColor"
          class="bi bi-geo-alt-fill"
          viewBox="0 0 16 16"
        >
          <path
            d="M8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10zm0-7a3 3 0 1 1 0-6 3 3 0 0 1 0 6z"
          />
        </svg>
        <a href="#" class="btn btn-basic">
          <h6>9 Geoffery Jones Court, 345-347 Harlesden Road, NW10 3RW</h6>
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "FooterP",
};
</script>

<style scoped>
body {
  color: white !important;
  underline: none !important;
}

.foot {
  color: black !important;
}

.text {
  font-size: 15px;
  line-height: 1;
  color: black !important;
  padding-bottom: 20px;
}

.colorr {
  color: black !important;
  font-size: 18px;
  text-align: center;
}

.footer {
  background-color: black !important;
  line-height: 28px;
  font-size: 18px;
  padding-top: 2% !important;
  padding-bottom: 2% !important;
  box-sizing: border-box;
}

a.nav-link {
  color: black !important;
}

.list {
  list-style: none;
  font-size: 100%;
  font-weight: 100px;
}

.size {
  height: 75%;
  width: 100%;
}

.nav-link:focus,
.nav-link:hover {
  color: orangered !important;
}
</style>
