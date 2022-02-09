<template>
  <div class="experienced-wrapper pl-24 pr-24 pt-6 pb-48">
    <h1 class="text-center text-4xl font-bold mt-12 text-white">{{ msg }}</h1>
    <div class="experienced-wrapper flex mt-14">
      <div class="card px-12 py-8 rounded-md w-full">
        <h3 class="text-xl font-bold text-white">
          Average Front End Experience
        </h3>
        <h1 class="text-4xl font-extrabold text-white mt-2">5+ Years</h1>
      </div>

      <div class="card px-12 py-8 rounded-md ml-8 w-full">
        <h3 class="text-xl font-bold text-white">Average Vue.js Experience</h3>
        <h1 class="text-4xl font-extrabold text-white mt-2">2+ Years</h1>
      </div>

      <div class="card px-10 py-8 rounded-md ml-8 w-full">
        <h3 class="text-xl font-bold text-white">
          Average Technology Experience
        </h3>
        <h1 class="text-4xl font-extrabold text-white mt-2">9+ Years</h1>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      msg: "Experienced Developers Available",
    };
  },
};
</script>

<style scoped>
div.experienced-wrapper {
  background-color: #242d55;
}

div.card {
  background-color: #2a3565;
}
</style>
