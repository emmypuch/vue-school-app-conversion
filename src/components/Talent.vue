<template>
  <div>
    <!-- Hire Talent Section Begins -->
    <section id="hire-talent-container" class="">
      <div
        class="hire-talent-flex md:flex-col md:justify-center md:items-center lg:flex lg:justify-between lg:pl-20 lg:pr-20 lg:pt-20"
      >
        <div class="hire-talent-description">
          <h1
            class="md:text-lg md:pl-0 md:text-center lg:text-6xl font-extrabold text-white lg:pl-8 leading-tight"
          >
            Hire the Best <br />
            Vue.js talent
          </h1>
          <p
            class="lg:text-base lg:pl-10 lg:mt-8 md:pl-0 md:mt-4 md:text-center font-semibold"
          >
            Engage with the Vue School community of experienced Vue.js
          </p>
          <p class="text2 pl-10 font-semibold md:text-center">
            Professionals with the skillsets you need
          </p>
          <Button />
        </div>
        <div
          class="hire-talent-description lg:pr-12 md:pr-0 md:flex md:justify-center md:items-center"
        >
          <img :src="ImageContent" alt="Vue School Logo" class="max-w-full" />
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import Button from "./Button.vue";
const ImageContent = require("../assets/images/main.svg");
export default {
  data() {
    return {
      ImageContent,
    };
  },
  components: {
    Button,
  },
};
</script>

<style scoped>
section#hire-talent-container {
  background-color: #242d55;
}

div.hire-talent-description p {
  color: #aeb6e3;
}
</style>
