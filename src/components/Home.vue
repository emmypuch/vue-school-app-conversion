<template>
  <div>
    <Header />
    <Talent />
    <LogoCard />
    <DirectAccess />
  </div>
</template>

<script>
import Header from "./Header.vue";
import Talent from "./Talent.vue";
import LogoCard from "./LogoCard.vue";
import DirectAccess from "./DirectAccess.vue";

export default {
  name: "Home",
  components: {
    Header,
    Talent,
    LogoCard,
    DirectAccess,
  },
};
</script>
