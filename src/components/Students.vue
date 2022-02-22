<template>
  <section>
    <div class="container">
      <div class="row">
        <h2 class="text-center mt-5">What Students Say</h2>
        <div class="col-3 d-flex align-items-center justify-content-center">
          <i class="fa-solid fa-arrow-left"></i>
        </div>
        <div class="col-6">
          <div class="d-flex justify-content-center align-items-center mt-5">
            <img
              class="rounded-circle"
              src="../assets/img/1-100x100.jpg"
              alt="1"
            />
            <img
              class="rounded-circle p-3 wi-25"
              src="../assets/img/2-100x100.jpg"
              alt="2"
            />
            <img
              class="rounded-circle"
              src="../assets/img/4-100x100.jpg"
              alt="3"
            />
          </div>
          <div class="text-center mt-5">
            <h4>Paints of the Future</h4>
            <i v-for="n in 5" :key="n" class="fa-solid fa-star"></i>
            <p class="mt-3">
              The response to your MasterStudy has been really overwhelming!
              Those who participated in the workshop are spreading the word here
              on campus and the "buzz" is on. The VP of Instruction wants you to
              come back! Her goal is to have more faculty tiained. She also
              wants to attend a workshop herself. Our President told me
              Masterstudy needs to be the cornerstone of our sucess program.
            </p>
          </div>
        </div>
        <div class="col-3 d-flex align-items-center justify-content-center">
          <i class="fa-solid fa-arrow-right"></i>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "students",
};
</script>

<style lang="scss" scoped>
.fa-star {
  color: #f2b91e;
}

.wi-25 {
  width: 35%;
}
</style>