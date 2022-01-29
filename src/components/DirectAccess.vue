<template>
  <div class="direct-section pl-24 pr-24 pt-16 pb-64">
    <div class="direct-section-card-container relative pr-6 pt-6 pb-6 flex">
      <div
        class="card absolute bg-white shadow-md w-full rounded-md pl-10 pr-10 pb-14 pt-6"
      >
        <h1 class="text-center font-bold text-4xl mt-6">{{ msg }}</h1>
        <div class="dev-container flex mt-16 justify-center">
          <div class="flex-shrink-0">
            <img :src="Image" alt="dev" />
          </div>
          <div class="dev-content ml-6">
            <h3 class="text-2xl font-bold">Find your next Vue.js Developer</h3>
            <p class="mt-2 text-base font-medium">
              Our community is a massive global talent pool. Professionals and
              enthusiasts from all over the world are looking <br />
              for their next job using Vue.js through our platform. Find them
              first and help them develop by becoming part of <br />
              your team.
            </p>
          </div>
        </div>
        <div class="dev-container flex mt-10 justify-center">
          <div>
            <img :src="ImageSkill" alt="skill" />
          </div>
          <div class="dev-content ml-6">
            <h3 class="text-2xl font-bold">Skills based Hiring</h3>
            <p class="mt-2 text-base font-medium">
              Every tech stack is unique and you need to know that your
              developers have the required skills to work effectively. <br />
              Here we search based on required skills. help them develop by
              becoming part of your team.
            </p>
          </div>
        </div>
        <div class="dev-container flex mt-10 justify-center">
          <div>
            <img :src="ImageTime" alt="time" />
          </div>
          <div class="dev-content ml-6">
            <h3 class="text-2xl font-bold">Cut your time to Hire</h3>
            <p class="mt-2 text-base font-medium">
              Every tech stack is unique and you need to know that your
              developers have the required skills to work effectively. <br />
              Here we search based on required skills. help them develop by
              becoming part of your team.
            </p>
          </div>
        </div>
      </div>
    </div>
    <!-- <DevSearch /> -->
  </div>
</template>

<script>
// import DevSearch from "./DevSearch.vue";
const Image = require("../assets/images/devs.svg");
const ImageSkill = require("../assets/images/skills.svg");
const ImageTime = require("../assets/images/time.svg");
export default {
  components: {},
  data() {
    return {
      msg: "Direct Access Hiring",
      Image,
      ImageSkill,
      ImageTime,
    };
  },
};
</script>

<style scoped>
div.direct-section {
  background-color: #fbfcff;
}

div.card h1,
h3 {
  color: #242d55;
}

div.card {
  top: -140px;
}

p {
  color: #646c95;
}
</style>
