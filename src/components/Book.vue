<template>
  <section class="bg-book">
    <div class="container">
      <div class="row">
        <div class="col-6 pt-5">
          <h2 class="text-center">
            Get My Exclusive Investing <br />
            Book just for $19.50
          </h2>
          <p class="text-center">
            Vestibulum imentum eu urna vel cursus. Aenean <br />
            vehicula quam quam, vitae pellentesque urna <br />
            elementum cursus.
          </p>
          <img class="img-fluid" src="../assets/img/amazon.png" alt="Amazon" />
        </div>
        <div class="col-6">
          <img class="img-fluid pt-4" src="../assets/img/book.png" alt="Book" />
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Book",
};
</script>

<style lang="scss" scoped>
.bg-book {
  background-image: url("../assets/img/slider_1-1917x607-1914x606.jpg");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
</style>