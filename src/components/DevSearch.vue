<template>
  <div class="pl-24 pr-24 pt-32 flex justify-center items-center">
    <h1 class="text-center text-4xl font-bold">{{ msg }}</h1>
    <div class="dev-search-numbers-wrapper relative">
      <div class="number-container absolute"></div>
      <div
        class="dev-search-card-container flex justify-between bg-red-500 p-6"
      >
        <div class="card-image">
          <img src="" alt="" />
        </div>
        <div class="card-content">
          <h3>Create Account</h3>
          <p>Gain access to our data base of 100’s of Vue developers</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      msg: "How Dev Search Works",
    };
  },
};
</script>

<style scoped>
div {
  background-color: #fbfcff;
}

h1 {
  color: #242d55;
}
</style>
