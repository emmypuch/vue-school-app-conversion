<template>
  <div>
    <Header />
    <Talent />
  </div>
</template>

<script>
import Header from "./Header.vue";
import Talent from "./Talent.vue";

export default {
  name: "Home",
  components: {
    Header,
    Talent,
  },
};
</script>
