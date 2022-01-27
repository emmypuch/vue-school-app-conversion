<template>
  <div>
    <div id="button" class="mt-20 pl-10">
      <a
        href="#"
        class="btn1 text-white text-lg px-8 py-6 leading-tight rounded-full font-bold transition-all focus:outline-none focus:ring-2"
      >
        REQUEST ACCESS
      </a>
      <a
        href="#"
        class="btn2 bg-white text-lg px-8 ml-4 py-6 leading-tight rounded-full font-bold transition-all focus:outline-none focus:ring-2"
        >APPLY AS DEVELOPER</a
      >
    </div>
    <Access />
  </div>
</template>

<script>
import Access from "./Access.vue";
export default {
  components: {
    Access,
  },
};
</script>

<style scoped>
.btn1 {
  background-color: #5ac0fe;
  cursor: pointer;
}

.btn1:hover {
  background-color: #57d7ff;
}

.btn2 {
  color: #667cff;
  cursor: pointer;
}

.btn2:hover {
  background-color: #e3edff;
}
</style>
