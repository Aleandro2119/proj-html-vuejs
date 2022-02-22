<template>
  <section>
    <div class="container">
      <h2 class="text-center p-4">Why my Courses?</h2>
      <div class="row gy-5">
        <div class="col-12 d-flex flex-wrap">
          <div
            v-for="(element, index) in elements"
            :key="index"
            class="col-6 p-4 box"
          >
            <h4 class="">{{ element.title }}</h4>
            <p>{{ element.text }}</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Courses",

  data() {
    return {
      elements: [
        {
          title: "Entrepreneurship",
          text: "Vestibulum vitae aliquam nunc. Suspendisse mollis metus ac tellus egestas pharetra. Suspendisse at viverra purus. Pellentesque nec posuere ligula, eu congue leo. Integer vulputate tempor arcu. Vestibulum vulputate",
        },
        {
          title: "Accelerated learning",
          text: "Vestibulum vitae aliquam nunc. Suspendisse mollis metus ac tellus egestas pharetra. Suspendisse at viverra purus. Pellentesque nec posuere ligula, eu congue leo. Integer vulputate tempor arcu. Vestibulum vulputate",
        },
        {
          title: "Productivity",
          text: "Vestibulum vitae aliquam nunc. Suspendisse mollis metus ac tellus egestas pharetra. Suspendisse at viverra purus. Pellentesque nec posuere ligula, eu congue leo. Integer vulputate tempor arcu. Vestibulum vulputate",
        },
        {
          title: "Life Coaching",
          text: "Vestibulum vitae aliquam nunc. Suspendisse mollis metus ac tellus egestas pharetra. Suspendisse at viverra purus. Pellentesque nec posuere ligula, eu congue leo. Integer vulputate tempor arcu. Vestibulum vulputate",
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
.box {
  background-color: white;
  border-left: 4px solid #f2b91e;
}
</style>