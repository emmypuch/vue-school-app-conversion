<template>
  <div class="card-content pl-24 pr-24 pt-20 pb-10">
    <div class="card-wrapper p-6 w-full rounded-md">
      <h5 class="pl-6 pt-2 text-white text-base font-medium">{{ msg }}</h5>
      <div
        class="skillset-logo-wrapper flex items-center justify-between overflow-auto ml-4 mt-10"
      >
        <div class="flex flex-col items-center space-y-3 w-28 flex-shrink-0">
          <li class="list-none">
            <img :src="Image" alt="vue.js" class="h-12" />
          </li>
          <div class="text-base font-medium">Vue.js</div>
        </div>
        <div class="flex flex-col items-center space-y-3 w-28 flex-shrink-0">
          <li class="list-none">
            <img :src="ImageNuxt" alt="nuxt.js" class="h-12" />
          </li>
          <div class="text-base font-medium">Nuxt.js</div>
        </div>
        <div class="flex flex-col items-center space-y-3 w-28 flex-shrink-0">
          <li class="list-none">
            <img :src="ImageVuex" alt="vuex" class="h-12" />
          </li>
          <div class="text-base font-medium">Vuex</div>
        </div>
        <div class="flex flex-col items-center space-y-3 w-28 flex-shrink-0">
          <li class="list-none">
            <img :src="ImageJest" alt="testing & jest" />
          </li>
          <div class="text-base font-medium">Testing & Jest</div>
        </div>
        <div class="flex flex-col items-center space-y-3 w-28 flex-shrink-0">
          <li class="list-none"><img :src="ImageGraphql" alt="graphql" /></li>
          <div class="text-base font-medium">GraphQl</div>
        </div>
        <div class="flex flex-col items-center space-y-3 w-28 flex-shrink-0">
          <li class="list-none">
            <img :src="ImageJavaScript" alt="javascript" />
          </li>
          <div class="text-base font-medium">JavaScript</div>
        </div>
        <div class="flex flex-col items-center space-y-3 w-28 flex-shrink-0">
          <li class="list-none"><img :src="ImageStory" alt="storybook" /></li>
          <div class="text-base font-medium">Storybook</div>
        </div>
        <div class="flex flex-col items-center space-y-3 w-28 flex-shrink-0">
          <li class="list-none"><img :src="ImageFirebase" alt="firebase" /></li>
          <div class="text-base font-medium">Firebase Suite</div>
        </div>
        <div class="flex flex-col items-center space-y-3 w-28 flex-shrink-0">
          <li class="list-none">
            <img :src="ImageTypeScript" alt="typescript" class="h-12" />
          </li>
          <div class="text-base font-medium">TypeScript</div>
        </div>
        <div class="flex flex-col items-center space-y-3 w-28 flex-shrink-0">
          <li class="list-none">
            <img :src="ImageVite" alt="vite" class="h-12" />
          </li>
          <div class="text-base font-medium">Vite</div>
        </div>
      </div>
      <!-- Second Column -->
      <div
        class="skillset-logo-wrapper flex items-center justify-between overflow-auto ml-4 mt-6"
      >
        <div class="flex flex-col items-center space-y-3 w-28 flex-shrink-0">
          <li class="list-none">
            <img :src="ImageVuetify" alt="vuetify" class="h-12" />
          </li>
          <div class="text-base font-medium">Vuetify</div>
        </div>
        <div class="flex flex-col items-center space-y-3 w-28 flex-shrink-0">
          <li class="list-none">
            <img :src="ImageLaravel" alt="laravel" class="h-12" />
          </li>
          <div class="text-base font-medium">Laravel</div>
        </div>
        <div class="flex flex-col items-center space-y-3 w-28 flex-shrink-0">
          <li class="list-none">
            <img :src="ImageTailwind" alt="tailwind" class="h-12" />
          </li>
          <div class="text-base font-medium">Tailwind</div>
        </div>
        <div class="flex flex-col items-center space-y-3 w-28 flex-shrink-0">
          <li class="list-none">
            <img :src="ImageNode" alt="node" />
          </li>
          <div class="text-base font-medium">Node</div>
        </div>
        <div class="flex flex-col items-center space-y-3 w-28 flex-shrink-0">
          <li class="list-none"><img :src="ImageRest" alt="Rest APIs" /></li>
          <div class="text-base font-medium">Rest APIs</div>
        </div>
        <div class="flex flex-col items-center space-y-3 w-28 flex-shrink-0">
          <li class="list-none">
            <img :src="ImageWebsocket" alt="websockets" />
          </li>
          <div class="text-base font-medium">Websockets</div>
        </div>
        <div class="flex flex-col items-center space-y-3 w-28 flex-shrink-0">
          <li class="list-none"><img :src="ImageQuasar" alt="quasar" /></li>
          <div class="text-base font-medium">Quasar</div>
        </div>
        <div class="flex flex-col items-center space-y-3 w-28 flex-shrink-0">
          <li class="list-none"><img :src="ImageCypress" alt="cypress" /></li>
          <div class="text-base font-medium">Cypress</div>
        </div>
        <div class="flex flex-col items-center space-y-3 w-28 flex-shrink-0">
          <li class="list-none">
            <img :src="ImageReact" alt="React" class="h-12" />
          </li>
          <div class="text-base font-medium">React</div>
        </div>
        <div class="flex flex-col items-center space-y-3 w-28 flex-shrink-0">
          <li class="list-none">
            <img :src="ImageAngular" alt="angular" class="h-12" />
          </li>
          <div class="text-base font-medium">Angular</div>
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
const ImageVuetify = require("../assets/images/vuetify.svg");
const ImageLaravel = require("../assets/images/laravel.svg");
const ImageTailwind = require("../assets/images/tailwind.svg");
const ImageNode = require("../assets/images/node.svg");
const ImageRest = require("../assets/images/rest.svg");
const ImageWebsocket = require("../assets/images/websockets.svg");
const ImageQuasar = require("../assets/images/quasar.svg");
const ImageCypress = require("../assets/images/cypress.svg");
const ImageReact = require("../assets/images/react.svg");
const ImageAngular = require("../assets/images/angular.svg");
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
      ImageVuetify,
      ImageLaravel,
      ImageTailwind,
      ImageNode,
      ImageRest,
      ImageWebsocket,
      ImageQuasar,
      ImageCypress,
      ImageReact,
      ImageAngular,
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

div.card-wrapper h5,
div {
  color: #aeb6e3;
}
</style>
