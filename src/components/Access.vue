<template>
  <div class="pl-10 pb-10">
    <div class="access-container flex p-4 rounded-md space-x-2 mt-24 w-full">
      <div
        class="image p-3 rounded-md flex-shrink-0 justify-items-center items-center flex"
      >
        <img :src="Image" alt="timer" />
      </div>
      <div class="text-content">
        <div class="text1">
          <h5 class="font-medium text-base">Early Access</h5>
        </div>
        <div class="text2">
          <p class="text-white font-medium text-base">
            The Vue School hiring program is currently in beta. <br />
            We do follow a first come, first serve waiting list.
          </p>
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
      Image,
    };
  },
};
</script>

<style scoped>
div.access-container {
  background-color: steelblue;
  opacity: 0.7;
}

/* div.image {
  background-color: #55d8ff;
  opacity: 1;
} */

.text1 h5 {
  color: #55d8ff;
}
</style>
