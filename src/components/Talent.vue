<template>
  <div>
    <!-- Hire Talent Section Begins -->
    <section id="hire-talent-container" class="">
      <div class="hire-talent-flex flex justify-between pl-20 pr-20 pt-20">
        <div class="hire-talent-description">
          <h1 class="text-6xl font-extrabold text-white pl-8 leading-tight">
            Hire the Best <br />
            Vue.js talent
          </h1>
          <p class="text1 pl-10 mt-8 font-semibold">
            Engage with the Vue School community of experienced Vue.js
          </p>
          <p class="text2 pl-10 font-semibold">
            Professionals with the skillsets you need
          </p>
          <Button />
        </div>
        <div class="hire-talent-description pr-12">
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
  background-color: #28335d;
}

div.hire-talent-description p {
  color: #aeb6e3;
}
</style>
