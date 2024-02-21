<script>
export default {
  props: ["menuItemsFromProp"],

  data() {
    return {
      menuItems: [
        { title: "Home" },
        { title: "About" },
        { title: "Process" },
        { title: "service" },
        { title: "Team" },
        { title: "Blog" },
      ],
    };
  },

  methods: {},

  mounted() {
    console.log(`mounted lifecycle`);
  },
};
</script>

<template>
  <!-- ###top header  -->
  <div class="top">
    <div class="hour">
      <div>
        <i class="fa-solid fa-clock"></i>
      </div>
      <div>
        <span>Open-Hours: Mon-Sat - 9:00-18:00</span>
      </div>
    </div>
    <div class="social-logo">
      <div>
        <i class="fa-solid fa-phone"></i>
      </div>
      <div>
        <span>+1(305)1234-5678</span>
      </div>
      <div>
        <i class="fa-solid fa-envelope"></i>
      </div>
      <div>
        <span>hello@example.com</span>
      </div>
      <div>
        <i class="fa-brands fa-facebook-f"></i>
      </div>
      <div>
        <i class="fa-brands fa-twitter"></i>
      </div>
      <div>
        <i class="fa-brands fa-linkedin-in"></i>
      </div>
    </div>
  </div>

  <div class="headInsurance">
    <!-- #### header  -->
    <div class="justify-content-center d-flex">
      <nav class="navbar navbar-expand-lg">
        <div class="logo-wrapper">
          <img class="logo" src="/img/nexgen-logo.svg" />
        </div>
        <div class="navbar-collapse" id="navbarTogglerDemo03">
          <ul class="navbar-nav mb-lg-0">
            <li v-for="item in menuItemsFromProp">{{ item.title }}</li>
          </ul>
          <form class="d-flex" role="search">
            <button class="btn btn-outline-success" type="submit">
              GET IN TOUCH
            </button>
          </form>
        </div>
      </nav>
    </div>
    <div class="d-flex justify-content-end mt-10">
      <div class="text-insurance">
        <p>FUSIONS & ACQUISITIONS</p>
        <h1>Insurance Consulting</h1>
        <div class="input-insurance d-flex justify-content-start">
          <div>
            <input
              type="text"
              class="form-control form-control-lg"
              placeholder="Name"
            />
          </div>
          <div>
            <input
              type="text"
              class="form-control form-control-lg"
              placeholder="Email"
            />
          </div>
        </div>
        <div class="input-insurance d-flex justify-content-start mt-2">
          <div>
            <input
              type="text"
              class="form-control form-control-lg"
              placeholder="Phone"
            />
          </div>
          <div>
            <input
              type="text"
              class="form-control form-control-lg"
              placeholder="More Info"
            />
          </div>
        </div>
        <div class="input-insurance d-flex justify-content-start mt-4">
          <button type="button" class="btn btn-outline-secondary btn-lg">
            GET IN TOUCH
          </button>
          <button type="button" class="btn btn-secondary btn-lg">
            READ MORE
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.top {
  color: white;
  background-color: #132e43;
  padding: 10px;
  display: flex;
  justify-content: space-around;
}
.hour {
  display: flex;
  gap: 10px;
}
.logo-wrapper {
  padding-right: 300px;
}
.logo {
  width: 120px;
}
.navbar-nav li {
  padding: 0 10px;
  text-transform: uppercase;
}
.mt-10 {
  margin-top: 100px;
}
.social-logo {
  display: flex;
  gap: 10px;
}
.headInsurance {
  width: 100%;
  height: 750px;
  background-color: aqua;
  background-image: url("/img/bg-6.jpg");
  background-position: center;
  background-size: cover;
}
.text-insurance {
  width: 50%;
  align-items: flex-end;
}
.form-control {
  background: #ddd !important;
  width: 95% !important;
}
.input-insurance button:last-child {
  margin-left: 15px;
}
</style>
