<template>
  <header>
    <div class="container">
      <div class="row">
        <div class="col d-flex justify-content-between align-items-center">
          <img src="../assets/img/MasterStudy-1.svg" alt="" />
          <div id="navbar">
            <ul class="d-flex">
              <li><a href="#">Courses</a></li>
              <li><a href="#">Course Formats</a></li>
              <li><a href="#">Add Course</a></li>
              <li><a href="#">Pages</a></li>
              <li><a href="#">Demos</a></li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
header {
  background-color: white;
  padding: 30px;

  li {
    list-style-type: none;

    a {
      text-decoration: none;
      padding-left: 20px;
      color: black;

      .fa-brands {
        color: black;
      }
    }
  }
}
</style>