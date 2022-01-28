<template>
  <div class="card-content pl-24 pr-24 pt-20 pb-10">
    <div
      class="card-wrapper p-4 flex justify-items-center items-center w-full rounded-md"
    >
      <h5 class="p-4 text-white text-base font-medium">{{ msg }}</h5>
      <div class="card-logos grid grid-cols-2 grid-rows-2">
        <div class="card-logo-col1">
          <img :src="Image" alt="timer" />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
const Image = require("../assets/images/block-timer.svg");
export default {
  data() {
    return {
      msg: "Filter by skillset:",
      Image,
    };
  },
};
</script>

<style scoped>
div.card-content {
  background-color: #242d55;
}

div.card-wrapper {
  background-color: #313d70;
}

div.card-wrapper h5 {
  color: #aeb6e3;
}
</style>
