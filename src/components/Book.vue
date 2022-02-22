<template>
  <section class="bg-book">
    <div class="container">
      <div class="row">
        <div class="col-6 pt-5">
          <h2 class="text-center text-color">
            Get My Exclusive Investing <br />
            Book just for $19.50
          </h2>
          <p class="text-center fs-4 text-white pt-4">
            Vestibulum imentum eu urna vel cursus. Aenean <br />
            vehicula quam quam, vitae pellentesque urna <br />
            elementum cursus.
          </p>
          <div class="d-flex justify-content-center pt-4">
            <img
              class="img-fluid"
              src="../assets/img/amazon.png"
              alt="Amazon"
            />
          </div>
        </div>
        <div class="col-6">
          <img class="img-fluid pt-4" src="../assets/img/book.png" alt="Book" />
        </div>
      </div>
    </div>

    <div class="menu">
      <ul class="position-menu text-center">
        <li>
          <a href="#"><i class="fa-solid fa-desktop"></i></a>
        </li>
        <li>
          <a href="#"><i class="fa-regular fa-life-ring"></i></a>
        </li>
        <li>
          <a href="#"><i class="fa-solid fa-wrench"></i></a>
        </li>
        <li>
          <a href="#"><i class="fa-solid fa-cart-shopping"></i></a>
        </li>
        <li>
          <a href="#"><i class="fa-solid fa-mobile-screen-button"></i></a>
        </li>
      </ul>
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

.text-color {
  color: #f2b91e;
}

li {
  list-style-type: none;
  background-color: white;
  padding: 5px;

  a {
    text-decoration: none;
    color: #4d5156;
  }
}

.menu {
  position: relative;

  .position-menu {
    position: absolute;
    right: 0px;
    bottom: 300px;
  }
}
</style>