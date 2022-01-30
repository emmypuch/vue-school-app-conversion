<template>
  <div class="dev-search-wrapper pl-24 pr-24 pt-14 relative mt-48">
    <h1 class="text-center text-4xl font-bold">{{ msg }}</h1>
    <div class="dev-search-numbers-wrapper">
      <div class="number-container rounded-xl"></div>
    </div>
    <div
      class="dev-search-card-container flex bg-white shadow-lg rounded-sm p-6 mt-10"
    >
      <div class="card-image">
        <img :src="Image" alt="dev" class="" />
      </div>
      <div class="card-content ml-6">
        <h3 class="text-2xl font-bold">Create Account</h3>
        <p class="mt-2 text-base font-medium">
          Gain access to our data base of 100’s of Vue developers
        </p>
      </div>
    </div>

    <div
      class="dev-search-card-container flex bg-white shadow-lg rounded-sm p-6 mt-10"
    >
      <div class="card-image">
        <img :src="Image" alt="dev" class="" />
      </div>
      <div class="card-content ml-6">
        <h3 class="text-2xl font-bold">Create Account</h3>
        <p class="mt-2 text-base font-medium">
          Gain access to our data base of 100’s of Vue developers
        </p>
      </div>
    </div>
  </div>
</template>

<script>
const Image = require("../assets/images/devs.svg");
export default {
  data() {
    return {
      msg: "How Dev Search Works",
      Image,
    };
  },
};
</script>

<style scoped>
div.dev-search-wrapper {
  background-color: #fbfcff;
}

h1 {
  color: #242d55;
}

div.card-content h3 {
  color: #242d55;
}

p {
  color: #646c95;
}
</style>
