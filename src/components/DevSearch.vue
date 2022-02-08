<template>
  <div class="dev-search-wrapper pl-24 pr-24 pt-14 relative mt-48">
    <h1 class="text-center text-4xl font-bold mt-12">{{ msg }}</h1>
    <div class="dev-search-numbers-wrapper">
      <div class="number-container rounded-xl"></div>
    </div>
    <div
      class="dev-search-card-container flex bg-white shadow-lg rounded-sm p-8 mt-16"
    >
      <div class="card-image">
        <img :src="ImagePen" alt="dev" class="h-20" />
      </div>
      <div class="card-content ml-6">
        <h3 class="text-2xl font-bold">Create Account</h3>
        <p class="mt-2 text-base font-medium">
          Register and subscribe to get secure access to our developer database.
        </p>
      </div>
    </div>

    <div
      class="dev-search-card-container flex bg-white shadow-lg rounded-sm p-8 mt-10"
    >
      <div class="card-image">
        <img :src="ImageSearch" alt="dev" class="h-20" />
      </div>
      <div class="card-content ml-6">
        <h3 class="text-2xl font-bold">Search for your ideal Vue developer</h3>
        <p class="mt-2 text-base font-medium">
          Utilise our easy-to-use interface to select the exact criteria for
          your ideal candidate. Search options include location, skillsets,
          experience and more.
        </p>
      </div>
    </div>

    <div
      class="dev-search-card-container flex bg-white shadow-lg rounded-sm p-8 mt-10"
    >
      <div class="card-image">
        <img :src="ImageEnvelop" alt="dev" class="h-20" />
      </div>
      <div class="card-content ml-6">
        <h3 class="text-2xl font-bold">Connect directly with your candidate</h3>
        <p class="mt-2 text-base font-medium">
          Browse the list of developers and connect with the candidates that fit
          your criteria
        </p>
      </div>
    </div>

    <div
      class="dev-search-card-container flex bg-white shadow-lg rounded-sm p-8 mt-10"
    >
      <div class="card-image">
        <img :src="ImageArrow" alt="dev" class="h-20" />
      </div>
      <div class="card-content ml-6">
        <h3 class="text-2xl font-bold">Built to scale to your needs</h3>
        <p class="mt-2 text-base font-medium">
          Each subscription includes your ability to connect with up to 50
          developers per month on this introductory offer, with the option to
          purchase as many additional connections as you need!
        </p>
      </div>
    </div>
  </div>
</template>

<script>
const ImagePen = require("../assets/images/pen.png");
const ImageSearch = require("../assets/images/search.png");
const ImageEnvelop = require("../assets/images/envelop.png");
const ImageArrow = require("../assets/images/arrow.png");
export default {
  data() {
    return {
      msg: "How Dev Search Works",
      ImagePen,
      ImageSearch,
      ImageEnvelop,
      ImageArrow,
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
