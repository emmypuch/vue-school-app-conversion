<template>
  <div class="service-wrapper pl-24 pr-24 pt-14 mt-16 pb-24">
    <h1 class="text-center text-4xl font-bold mt-6 text-white">{{ msg }}</h1>
    <div class="service-card-wrapper flex justify-between mt-14">
      <div class="card p-10 rounded-md h-full">
        <img :src="ImageRay" alt="" class="h-20" />
        <h2 class="text-white text-3xl font-bold mt-6">Hands Off Hiring</h2>
        <p class="mt-4 mb-6 text-lg">
          We handle the entire hiring process for you, allowing you to focus on
          expanding your business rather than your development team.
        </p>
        <div class="border mt-20"></div>
        <ul class="mt-4">
          <div class="flex">
            <div class="circle mt-3"></div>
            <li class="ml-2 text-white text-lg font-bold">
              Profesional Vetting
            </li>
          </div>

          <div class="flex">
            <div class="circle mt-5"></div>
            <li class="ml-2 text-lg font-bold text-white mt-2">
              Faster Hiring Process
            </li>
          </div>

          <div class="flex">
            <div class="circle mt-5"></div>
            <li class="ml-2 text-lg font-bold text-white mt-2">
              Higher Quality Candidates
            </li>
          </div>

          <div class="flex">
            <div class="circle mt-5"></div>
            <li class="ml-2 text-lg font-bold text-white mt-2">
              Custom Realworld Tests + Assements
            </li>
          </div>

          <div class="flex">
            <div class="circle mt-5"></div>
            <li class="ml-2 text-lg font-bold text-white mt-2">
              3 Month Placement Guarantee
            </li>
          </div>
        </ul>
      </div>

      <div class="card p-10 rounded-md h-full ml-6">
        <img :src="ImageStar" alt="" class="h-20" />
        <h2 class="text-white text-3xl font-bold mt-6">Custom Assesments</h2>
        <p class="mt-4 mb-6 text-lg">
          We handle the entire hiring process for you, allowing you to focus on
          expanding your business rather than your development team.
        </p>
        <div class="border mt-20"></div>
        <ul class="mt-4">
          <div class="flex">
            <div class="circle mt-3"></div>
            <li class="ml-2 text-white text-lg font-bold">
              Identify hidden skills
            </li>
          </div>

          <div class="flex">
            <div class="circle mt-5"></div>
            <li class="ml-2 text-lg font-bold text-white mt-2">
              Reduce time to hire
            </li>
          </div>

          <div class="flex">
            <div class="circle mt-5"></div>
            <li class="ml-2 text-lg font-bold text-white mt-2">
              Create consistant hiring standards
            </li>
          </div>

          <div class="flex">
            <div class="circle mt-5"></div>
            <li class="ml-2 text-lg font-bold text-white mt-2">
              Custom Realworld Tests + Assements
            </li>
          </div>

          <div class="flex">
            <div class="circle mt-5"></div>
            <li class="ml-2 text-lg font-bold text-white mt-2">
              3 Month Placement Guarantee
            </li>
          </div>
        </ul>
      </div>

      <div class="card p-10 rounded-md ml-6">
        <img :src="ImagePeople" alt="" class="h-20" />
        <h2 class="text-white text-3xl font-bold mt-6">Team Training</h2>
        <p class="mt-4 mb-6 text-lg">
          To keep your team performing at its peak, you need to ensure they are
          up to date with the latest technological innovations and tools.
        </p>
        <div class="border mt-20"></div>
        <ul class="mt-4">
          <div class="flex">
            <div class="circle mt-3"></div>
            <li class="ml-2 text-white text-lg font-bold">
              Remove Knowledge gaps
            </li>
          </div>

          <div class="flex">
            <div class="circle mt-5"></div>
            <li class="ml-2 text-lg font-bold text-white mt-2">
              Maintain a highly effective team
            </li>
          </div>

          <div class="flex">
            <div class="circle mt-5"></div>
            <li class="ml-2 text-lg font-bold text-white mt-2">
              Produce better results
            </li>
          </div>

          <div class="flex">
            <div class="circle mt-5"></div>
            <li class="ml-2 text-lg font-bold text-white mt-2">
              Custom Realworld Tests + Assements
            </li>
          </div>

          <div class="flex">
            <div class="circle mt-5"></div>
            <li class="ml-2 text-lg font-bold text-white mt-2">
              Keep your developers engaged
            </li>
          </div>
        </ul>
      </div>
    </div>
    <div class="button flex justify-center items-center mt-12">
      <a
        href="#"
        class="text-white text-base font-bold rounded-full transition-all focus:outline-none focus:ring-2 px-8 py-6 leading-tight"
        >CONTACT US</a
      >
    </div>
  </div>
</template>

<script>
const ImageRay = require("../assets/images/ray.png");
const ImageStar = require("../assets/images/star.png");
const ImagePeople = require("../assets/images/people.png");
export default {
  data() {
    return {
      msg: "Additional Services",
      ImageRay,
      ImageStar,
      ImagePeople,
    };
  },
};
</script>

<style scoped>
div.service-wrapper {
  background-color: #242d55;
}

div.card {
  background-color: #1f264b;
}

div.border {
  border-color: rgb(53, 60, 92);
  border-bottom-width: 1px;
  height: 1px;
}

p {
  color: #aeb6e3;
}

.circle {
  background-color: #667cff;
  border-radius: 50%;
  height: 5px;
  width: 5px;
}

.button {
  background-color: #667cff;
}
</style>
