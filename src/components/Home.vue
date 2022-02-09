<template>
  <div>
    <Header />
    <Talent />
    <LogoCard />
    <ExperienceDev />
    <DirectAccess />
    <DevSearch />
    <Service />
    <Footer />
  </div>
</template>

<script>
import Header from "./Header.vue";
import Talent from "./Talent.vue";
import LogoCard from "./LogoCard.vue";
import ExperienceDev from "./ExperienceDev.vue";
import DirectAccess from "./DirectAccess.vue";
import DevSearch from "./DevSearch.vue";
import Service from "./Service.vue";
import Footer from "./Footer.vue";

export default {
  name: "Home",
  components: {
    Header,
    Talent,
    LogoCard,
    ExperienceDev,
    DirectAccess,
    DevSearch,
    Service,
    Footer,
  },
};
</script>
