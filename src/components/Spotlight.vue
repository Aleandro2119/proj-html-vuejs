<template>
  <section class="spotlight mt-5">
    <div class="container">
      <div class="row">
        <div class="col-12 d-flex flex-wrap position">
          <div class="col-3 d-flex justify-content-center align-items-center">
            <i class="fa-solid fa-user-group"> </i>
            <span class="fw-bold">3195</span>
            <span class="text-white">Online Learner</span>
          </div>

          <div class="col-3 d-flex justify-content-center align-items-center">
            <i class="fa-solid fa-film"> </i>
            <span class="fw-bold">23</span>
            <span class="text-white">Video Courses</span>
          </div>

          <div class="col-3 d-flex justify-content-center align-items-center">
            <i class="fa-solid fa-image"> </i>
            <span class="fw-bold">437</span>
            <span class="text-white">Sliders & Images</span>
          </div>

          <div class="col-3 d-flex justify-content-center align-items-center">
            <i class="fa-solid fa-thumbs-up"> </i>
            <span class="fw-bold">1440</span>
            <span class="text-white">Excellent Reviews</span>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Spotlight",
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

.fa-solid {
  font-size: 30px;
  color: white;
}

.position {
  margin-top: calc(450px / 2);
}

span {
  color: #f2b91e;
  font-size: 22px;
  padding-left: 10px;
}

p {
  color: white;
  padding-left: 20px;
}
</style>