<template>
  <div class="pl-24 pr-24 pt-32 flex justify-center items-center">
    <h1 class="text-center text-4xl font-bold">{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  data() {
    return {
      msg: "How Dev Search Works",
    };
  },
};
</script>

<style scoped>
div {
  background-color: #fbfcff;
}

h1 {
  color: #242d55;
}
</style>
