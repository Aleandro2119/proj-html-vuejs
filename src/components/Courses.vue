<template>
  <section>
    <div class="container">
      <h2 class="text-center pt-5 pb-5">Why my Courses?</h2>
      <div class="row">
        <div class="col-12 d-flex flex-wrap">
          <div
            v-for="(element, index) in elements"
            :key="index"
            class="col-6 p-4 box mb-4"
          >
            <h4>{{ element.title }}</h4>
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
          icon: "fa-solid fa-suitcase",
          text: "Vestibulum vitae aliquam nunc. Suspendisse mollis metus ac tellus egestas pharetra. Suspendisse at viverra purus. Pellentesque nec posuere ligula, eu congue leo. Integer vulputate tempor arcu. Vestibulum vulputate",
        },
        {
          title: "Accelerated learning",
          icon: "fa-solid fa-rocket",
          text: "Vestibulum vitae aliquam nunc. Suspendisse mollis metus ac tellus egestas pharetra. Suspendisse at viverra purus. Pellentesque nec posuere ligula, eu congue leo. Integer vulputate tempor arcu. Vestibulum vulputate",
        },
        {
          title: "Productivity",
          icon: "fa-solid fa-thumbs-up",
          text: "Vestibulum vitae aliquam nunc. Suspendisse mollis metus ac tellus egestas pharetra. Suspendisse at viverra purus. Pellentesque nec posuere ligula, eu congue leo. Integer vulputate tempor arcu. Vestibulum vulputate",
        },
        {
          title: "Life Coaching",
          icon: "fa-solid fa-gear",
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

  p {
    color: silver;
  }
}

.box:hover {
  background-color: #f2b91e;
}
</style>