<template>
  <section class="jumbotron">
    <div class="position">
      <div class="position-text">
        <h1>
          Start your Human <br />
          Revolution today
        </h1>
        <p>
          A wonderfull serenity has taken possession of my entire soul, like
          <br />
          these sweet mornings of spring which I enjoy with my whole heart.
        </p>
      </div>
      <div class="subscrive">
        <h4>Limited Sale: All courses with 55% off</h4>
        <input type="text" placeholder="Enter your email" />
        <button type="button">SUBSCRIBE</button>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.jumbotron {
  background-image: url("../assets/img/slide-1.jpg");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  height: 650px;
}

.position {
  position: relative;

  .position-text {
    position: absolute;
    top: 200px;
    left: 750px;
  }
}

.subscrive {
  position: absolute;
  top: 550px;
  left: 500px;
  background-color: #f2b91e;
  padding: 30px;
  border-radius: 10px;
}
</style>