<template>
  <div class="pl-10">
    <div class="access-container flex p-4 rounded-md space-x-4 mt-14">
      <div class="image p-3 rounded-md flex-shrink-0">
        <img :src="Image" alt="timer" />
      </div>
    </div>
  </div>
</template>

<script>
const Image = require("../assets/images/block-timer.svg");
export default {
  data() {
    return {
      Image,
    };
  },
};
</script>

<style scoped>
div.access-container {
  background-color: steelblue;
  opacity: 0.2;
}

div.image {
  background-color: cyan;
  opacity: 0.1;
}
</style>
