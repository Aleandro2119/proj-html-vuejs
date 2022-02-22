<template>
  <header>
    <div class="container">
      <div class="row">
        <div class="col d-flex justify-content-between align-items-center">
          <img src="../assets/img/MasterStudy-1.svg" alt="Logo" />
          <div id="navbar">
            <ul class="d-flex">
              <li><a href="#">Courses</a></li>
              <li><a href="#">Course Formats</a></li>
              <li>
                <a href="#">Add Courses<span>NEW</span></a>
              </li>
              <li><a href="#">Pages</a></li>
              <li><a href="#">Demos</a></li>
              <div class="d-flex ps-5">
                <li>
                  <a href="#"><i class="fa-brands fa-linkedin"></i></a>
                </li>
                <li>
                  <a href="#"><i class="fa-brands fa-instagram"></i></a>
                </li>
                <li>
                  <a href="#"><i class="fa-brands fa-facebook"></i></a>
                </li>
                <li>
                  <a href="#"><i class="fa-brands fa-twitter"></i></a>
                </li>
              </div>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style lang="scss" scoped>
header {
  background-color: white;
  padding: 30px;

  li {
    list-style-type: none;

    a {
      text-decoration: none;
      padding-left: 15px;
      color: black;

      .fa-brands {
        color: black;
      }
    }
  }
  span {
    background-color: red;
    font-size: 8px;
    padding: 2px 5px;
    border-radius: 2px;
    position: relative;
    bottom: 15px;
    right: 15px;
    color: white;
  }
}
</style>