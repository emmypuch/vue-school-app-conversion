<template>
  <div>
    <Header />
    <Talent />
    <LogoCard />
  </div>
</template>

<script>
import Header from "./Header.vue";
import Talent from "./Talent.vue";
import LogoCard from "./LogoCard.vue";

export default {
  name: "Home",
  components: {
    Header,
    Talent,
    LogoCard,
  },
};
</script>
