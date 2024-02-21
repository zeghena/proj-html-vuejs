<script>
export default {
  data() {
    return {
      cards: {
        top: [
          {
            title: "Audit & Assurance",
            description:
              "Some quick example text to build on the card title content.",
            icon: "fa-regular fa-folder-open",
          },
          {
            title: "Financial Advisory",
            description:
              "Some quick example text to build on the card title content.",
            icon: "fa-solid fa-network-wired",
          },
          {
            title: "Analytics and M&A",
            description:
              "Some quick example text to build on the card title content.",
            icon: "fa-solid fa-briefcase",
          },
        ],
        bottom: [
          {
            title: "Middle and Marketing",
            description:
              "Some quick example text to build on the card title content.",
            icon: "fa-regular fa-paper-plane",
          },
          {
            title: "Legal Consulting",
            description:
              "Some quick example text to build on the card title content.",
            icon: "fa-solid fa-chart-simple",
          },
          {
            title: "Regulatory Risk",
            description:
              "Some quick example text to build on the card title content.",
            icon: "fa-solid fa-globe",
          },
        ],
      },
    };
  },
};
</script>

<template>
  <div class="comp-exce">
    <div class="container">
      <p class="minititle littlefont">OUR BUSINESS AREAS</p>
      <h1 class="title">Excellence in Services</h1>
      <div class="post-title">
        <div>
          <p class="littlefont">
            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Facere,
            commodi aperiam ab ad sunt necessitatibus!
          </p>
          <p class="littlefont">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Earum
            nobis minus aspernatur.
          </p>
        </div>
        <div>
          <button type="button" class="btn btn-success">SEE ALL</button>
        </div>
      </div>
      <div class="portacard">
        <div
          v-for="row in cards"
          class="d-flex justify-content-center gap-5 mt-5"
        >
          <div v-for="card in row" class="card" style="width: 15rem">
            <div class="card-body">
              <div class="icon-card">
                <i :class="card.icon"></i>
                <a href="#" class="card-link"
                  ><i class="fa-solid fa-arrow-right"></i
                ></a>
              </div>
              <h5 class="card-title">{{ card.title }}</h5>
              <p class="card-text">
                {{ card.description }}
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.comp-exce {
  width: 100%;

  background-color: rgb(238, 244, 237);
}
.container {
  padding: 50px;
}
.title {
  font-weight: bold;
}
.post-title {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.icon-card {
  display: flex;
  justify-content: space-between;
}
.portacard {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}
</style>
