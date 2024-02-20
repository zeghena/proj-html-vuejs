<script></script>

<template>
  <div class="container2">
    <div class="text-left">
      <p class="minititle littlefont">ABOUT THE NETWORK</p>
      <h1 class="title">The Company</h1>
      <p class="littlefont">
        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Facere,
        commodi aperiam ab ad sunt necessitatibus!
      </p>
      <p class="littlefont">
        Lorem ipsum dolor sit, amet consectetur adipisicing elit. Earum nobis
        minus aspernatur.
      </p>
    </div>
    <div class="text-card">
      <div class="paragraph">
        <div class="minititle2">
          <i class="fa-solid fa-gift"></i>
          <h4 class="title2">Tradition</h4>
        </div>
        <p class="littlefont">
          Lorem ipsum dolor sit amet consectetur adipisicing elit.
        </p>
      </div>
      <div class="paragraph">
        <div class="minititle2">
          <i class="fa-solid fa-lock"></i>
          <h4 class="title2">Security</h4>
        </div>
        <p class="littlefont">
          Lorem ipsum dolor sit amet consectetur adipisicing elit.
        </p>
      </div>
      <div class="paragraph">
        <div class="minititle2">
          <i class="fa-solid fa-pen-to-square"></i>
          <h4 class="title2">Certificate</h4>
        </div>
        <p class="littlefont">
          Lorem ipsum dolor sit amet consectetur adipisicing elit.
        </p>
      </div>
      <div class="paragraph">
        <div class="minititle2">
          <i class="fa-solid fa-graduation-cap"></i>
          <h4 class="title2">Expertice</h4>
        </div>
        <p class="littlefont">
          Lorem ipsum dolor sit amet consectetur adipisicing elit.
        </p>
      </div>
    </div>
  </div>
</template>

<style>
.container2 {
  width: 100%;
  display: flex;
  background-color: rgb(18, 18, 18);
}
.text-left {
  width: 50%;
  padding: 80px;
  color: white;
}
.minititle {
  color: rgb(0, 166, 166);
}
.minititle2 {
  display: flex;
  align-items: center;
  gap: 15px;
  color: rgb(0, 166, 166);
}
.title {
  font-size: bold;
}
.title2 {
  color: white;
}
.text-card {
  width: 50%;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  color: white;
  margin: auto;
}
.paragraph {
  width: 200px;
  height: 120px;
  padding: 10px;
}
.littlefont {
  font-size: smaller;
}
</style>
