<template>
  <div class="service-wrapper pl-24 pr-24 pt-14 mt-16">
    <h1 class="text-center text-4xl font-bold mt-12 text-white">{{ msg }}</h1>
    <div class="service-card-wrapper flex justify-center items-center mt-8">
      <div class="card p-10 rounded-md">
        <img :src="Image" alt="" class="h-20" />
        <h2 class="text-white text-3xl font-bold mt-6">Hands Off Hiring</h2>
        <p class="mt-4 mb-6 text-lg">
          We handle the entire hiring process for you, allowing you to focus on
          expanding your business rather than your development team.
        </p>
        <div class="border mt-20"></div>
        <ul class="mt-4">
          <li>Profesional Vetting</li>
          <li>Faster Hiring Process</li>
          <li>Higher Quality Candidates</li>
          <li>Custom Realworld Tests + Assements</li>
          <li>3 Month Placement Guarantee</li>
        </ul>
      </div>

      <div class="card p-8 ml-6">
        <img :src="Image" alt="" class="h-20" />
        <h2>Hands Off Hiring</h2>
        <p>
          We handle the entire hiring process for you, allowing you to focus on
          expanding your business rather than your development team.
        </p>
      </div>

      <div class="card p-8 ml-6">
        <img :src="Image" alt="" class="h-20" />
        <h2>Hands Off Hiring</h2>
        <p>
          We handle the entire hiring process for you, allowing you to focus on
          expanding your business rather than your development team.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
const Image = require("../assets/images/search.png");
export default {
  data() {
    return {
      msg: "Additional Services",
      Image,
    };
  },
};
</script>

<style scoped>
div.service-wrapper {
  background-color: #242d55;
}

div.card {
  background-color: #1f264b;
}

div.border {
  border-color: rgb(53, 60, 92);
  border-bottom-width: 1px;
  height: 1px;
}

p {
  color: #aeb6e3;
}
</style>
