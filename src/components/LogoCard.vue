<template>
  <div class="card-content pl-24 pr-24 pt-20 pb-10">
    <div class="card-wrapper p-6 w-full rounded-md">
      <h5 class="p-6 text-white text-base font-medium">{{ msg }}</h5>
      <div
        class="skillset-logo-wrapper flex items-center justify-between overflow-auto ml-4"
      >
        <div class="flex flex-col items-center space-y-3 w-28 flex-shrink-0">
          <li><img :src="Image" alt="vue.js" class="h-12" /></li>
          <div>Vue.js</div>
        </div>
        <div class="flex flex-col items-center space-y-3 w-28 flex-shrink-0">
          <li><img :src="ImageNuxt" alt="nuxt.js" class="h-12" /></li>
          <div>Nuxt.js</div>
        </div>
        <div class="flex flex-col items-center space-y-3 w-28 flex-shrink-0">
          <li><img :src="ImageVuex" alt="vuex" class="h-12" /></li>
          <div>Vuex</div>
        </div>
        <div class="flex flex-col items-center space-y-3 w-28 flex-shrink-0">
          <li><img :src="ImageJest" alt="testing & jest" /></li>
          <div>Testing & Jest</div>
        </div>
        <div class="flex flex-col items-center space-y-3 w-28 flex-shrink-0">
          <li><img :src="ImageGraphql" alt="graphql" /></li>
          <div>GraphQl</div>
        </div>
        <div class="flex flex-col items-center space-y-3 w-28 flex-shrink-0">
          <li><img :src="ImageJavaScript" alt="javascript" /></li>
          <div>JavaScript</div>
        </div>
        <div class="flex flex-col items-center space-y-3 w-28 flex-shrink-0">
          <li><img :src="ImageStory" alt="storybook" /></li>
          <div>Storybook</div>
        </div>
        <div class="flex flex-col items-center space-y-3 w-28 flex-shrink-0">
          <li><img :src="ImageFirebase" alt="firebase" /></li>
          <div>Firebase Suite</div>
        </div>
        <div class="flex flex-col items-center space-y-3 w-28 flex-shrink-0">
          <li><img :src="ImageTypeScript" alt="typescript" class="h-12" /></li>
          <div>TypeScript</div>
        </div>
        <div class="flex flex-col items-center space-y-3 w-28 flex-shrink-0">
          <li><img :src="ImageVite" alt="vite" class="h-12" /></li>
          <div>Vite</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
const Image = require("../assets/images/vue.svg");
const ImageNuxt = require("../assets/images/nuxt.svg");
const ImageVuex = require("../assets/images/vuex.svg");
const ImageJest = require("../assets/images/jest.svg");
const ImageGraphql = require("../assets/images/graphql.svg");
const ImageJavaScript = require("../assets/images/javascript.svg");
const ImageStory = require("../assets/images/storybook.svg");
const ImageFirebase = require("../assets/images/firebase.svg");
const ImageTypeScript = require("../assets/images/typescript.svg");
const ImageVite = require("../assets/images/vite.svg");
export default {
  data() {
    return {
      msg: "Filter by skillset:",
      Image,
      ImageNuxt,
      ImageVuex,
      ImageJest,
      ImageGraphql,
      ImageJavaScript,
      ImageStory,
      ImageFirebase,
      ImageTypeScript,
      ImageVite,
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
