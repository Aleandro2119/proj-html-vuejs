<template>
  <section class="spotlight mt-5">
    <div class="container">
      <div class="row">
        <div class="col-12 d-flex flex-wrap position">
          <div class="col-3 d-flex justify-content-center align-items-center">
            <i class="fa-solid fa-user-group"> </i>
            <span>3195</span>
            <span class="text-white">Online Learner</span>
          </div>
          <div class="col-3 d-flex justify-content-center align-items-center">
            <i class="fa-solid fa-film"> </i>
            <span>23</span>
            <span class="text-white">Video Courses</span>
          </div>
          <div class="col-3 d-flex justify-content-center align-items-center">
            <i class="fa-solid fa-image"> </i>
            <span>437</span>
            <span class="text-white">Sliders & Images</span>
          </div>
          <div class="col-3 d-flex justify-content-center align-items-center">
            <i class="fa-solid fa-thumbs-up"> </i>
            <span>1440</span>
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
  display: flex;
  justify-content: center;
  align-items: center;
}

span {
  color: #f2b91e;
  font-size: 20px;
  padding-left: 10px;
}

p {
  color: white;
  padding-left: 20px;
}
</style>