<template>
  <div>
    <Header />
    <Talent />
    <LogoCard />
    <DirectAccess />
    <DevSearch />
    <Service />
  </div>
</template>

<script>
import Header from "./Header.vue";
import Talent from "./Talent.vue";
import LogoCard from "./LogoCard.vue";
import DirectAccess from "./DirectAccess.vue";
import DevSearch from "./DevSearch.vue";
import Service from "./Service.vue";

export default {
  name: "Home",
  components: {
    Header,
    Talent,
    LogoCard,
    DirectAccess,
    DevSearch,
    Service,
  },
};
</script>
