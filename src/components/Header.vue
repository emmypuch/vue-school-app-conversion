<template>
  <div id="navLinks">
    <!-- Header Section Begins -->
    <header class="flex justify-between pr-14 pl-14 pt-8">
      <div class="headerLogo">
        <a href="/"><img :src="Image" alt="Vue School Logo" class="w-32" /></a>
      </div>
      <div class="navbar">
        <div class="menu-lists text-white">
          <router-link
            to="/courses"
            id="listItems"
            class="m-4 font-bold text-sm"
            >COURSES</router-link
          >
          <a href="/#workshop" id="listItems" class="m-4 font-bold text-sm"
            >WORKSHOPS</a
          >
          <a href="/#plan" id="listItems" class="m-4 font-bold text-sm"
            >PLANS</a
          >
        </div>
        <!-- <div class="hamburger">
          <span class="line line1"></span>
          <span class="line line2"></span>
          <span class="line line3"></span>
        </div> -->
      </div>
      <div class="listItemsLinkContainer">
        <a
          href="/#contact"
          id="listItemsLink"
          class="text-white font-bold text-sm"
          >LOGIN</a
        >
      </div>
    </header>
  </div>
</template>

<script>
const Image = require("../assets/images/vueschool.svg");
export default {
  name: "Header",
  data() {
    return {
      Image,

      msg: "",
    };
  },
};
</script>

<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  overflow: hidden;
}

header {
  background-color: #242d55;
}
</style>
