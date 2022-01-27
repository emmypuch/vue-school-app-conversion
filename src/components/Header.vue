<template>
  <div id="navLinks">
    <header class="flex">
      <div class="headerLogo">
        <h1>Logo</h1>
        <!-- <a href="/"><img :src="Image" alt="" /></a> -->
      </div>
      <div class="navbar">
        <div class="menu-lists">
          <router-link to="/about" id="listItems">Courses</router-link>
          <a href="/#projects" id="listItems">Workshops</a>
          <a href="/#contact" id="listItems">Plans</a>
          <a href="/#contact" id="listItemsLink">Login</a>
        </div>
        <!-- <div class="hamburger">
          <span class="line line1"></span>
          <span class="line line2"></span>
          <span class="line line3"></span>
        </div> -->
      </div>
    </header>
  </div>
</template>

<script>
// const Image = require("../assets/images/headerLogo.png");
export default {
  name: "Header",
  data() {
    return {};
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

section#header {
  background-color: #28335d;
}
</style>
