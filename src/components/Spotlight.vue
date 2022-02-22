<template>
  <section class="spotlight mt-5">
    <div class="container">
      <div class="row">
        <div class="col-12">
          <div class="col-3">
            <i class="bi bi-people p-4"></i>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Spotlight",

  data() {
    return {
      boxes: [
        {
          number: "3195",
          text: "Online Learner",
          url: "#",
        },
        {
          number: "23",
          text: "Video Courses",
          url: "#",
        },
        {
          number: "437",
          text: "Sliders & Images",
          url: "#",
        },
        {
          number: "1440",
          text: "Excellent Reviews",
          url: "#",
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
.spotlight {
  background-image: url("../assets/img/counter-1919x1101.jpg");
  background-position: top;
  background-repeat: no-repeat;
  background-size: cover;
  height: 450px;
}
</style>