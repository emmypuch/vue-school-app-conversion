<template>
  <div class="direct-section pl-20 pr-20 pt-20">
    <div class="direct-section-card-container relative pr-6 pt-6 pb-8">
      <div class="card absolute bg-red-500 w-full rounded-md p-8">
        <h1>{{ msg }}</h1>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      msg: "Direct Access Hiring",
    };
  },
};
</script>

<style scoped>
div.direct-section {
  background-color: #fbfcff;
}

/* div.direct-section {
  background-color: #242d55;
} */

div.card {
  top: -120px;
}
</style>
