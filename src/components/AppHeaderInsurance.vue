<script></script>

<template>
  <!-- ###top header  -->
  <!-- <div class="top">
    <nav class="navbar bg-black">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">Fixed top</a>
      </div>
    </nav>
  </div> -->

  <!-- ###top header 2 -->
  <div class="top">
    <div>
      <span>Opern-Hours: Mon-Sat - 9:00-18:00</span>
    </div>
    <div class="social-logo">
      <div>
        <span>+1(305)1234-5678</span>
      </div>
      <div>
        <span>...</span>
      </div>
      <div>
        <span>...</span>
      </div>
      <div>
        <span>...</span>
      </div>
    </div>
  </div>

  <!-- #### header  -->
  <nav class="navbar navbar-expand-lg bg-body-tertiary">
    <div>
      <div class="navbar-collapse" id="navbarTogglerDemo03">
        <ul class="navbar-nav mb-lg-0">
          <li>
            <a class="nav-link" href="#">HOME</a>
          </li>
          <li>
            <a class="nav-link" href="#">ABOUT</a>
          </li>
          <li>
            <a class="nav-link" href="#">SERVICES</a>
          </li>
          <li>
            <a class="nav-link" href="#">PROCESS</a>
          </li>
          <li>
            <a class="nav-link" href="#">TEAM</a>
          </li>
          <li>
            <a class="nav-link" href="#">BLOG</a>
          </li>
        </ul>
        <form class="d-flex" role="search">
          <button class="btn btn-outline-success" type="submit">
            GET IN TOUCH
          </button>
        </form>
      </div>
    </div>
  </nav>
  <div class="headInsurance">
    <div class="text-insurance">
      <p>FUSIONS & ACQUISITIONS</p>
      <h1>Insurance Consulting</h1>
      <div class="btn-insurance btn-lg">
        <button type="button" class="btn btn-secondary btn-lg">Name</button>
        <button type="button" class="btn btn-secondary btn-lg">Email</button>
        <button type="button" class="btn btn-secondary btn-lg">Phone</button>
        <button type="button" class="btn btn-secondary btn-lg">
          More info
        </button>
      </div>
      <div>
        <button type="button" class="btn btn-outline-secondary btn-lg">
          GET IN TOUCH
        </button>
        <button type="button" class="btn btn-outline-secondary btn-lg">
          READ MORE
        </button>
      </div>
    </div>
  </div>
  Puppamelo
</template>

<style>
.top {
  color: white;
  background-color: #132e43;
  padding: 10px;
  display: flex;
}
.social-logo {
  display: flex;
}
.headInsurance {
  width: 100%;
  height: 450px;
  background-color: aqua;
  background-image: url("/img/bg-6.jpg");
  background-position: center;
  background-size: cover;
  display: flex;
  justify-content: flex-end;
}
.text-insurance {
  width: 50%;
  align-items: flex-end;
}
.btn-insurance {
  display: flex;
  flex-wrap: wrap;

  padding: 10px;
  gap: 15px;
}
</style>
