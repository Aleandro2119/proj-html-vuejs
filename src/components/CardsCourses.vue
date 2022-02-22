<template>
  <section class="cards-courses">
    <div class="container">
      <h2 class="text-center p-4">New Courses</h2>
      <div class="row">
        <div class="col-12 d-flex flex-wrap">
          <div class="col-4 p-3" v-for="(image, index) in images" :key="index">
            <img
              class="img-fluid"
              :src="require(`../assets/img/${image.poster}`)"
              alt=""
            />
            <p>{{ image.text }}</p>
            <p>{{ image.genres }}</p>
          </div>
        </div>
      </div>
      <div class="d-flex justify-content-center m-4">
        <a href="#">LOAD MORE</a>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "CardsCourses",

  data() {
    return {
      images: [
        {
          poster: "photo-1496307042754-b4aa456c4a2d-370x200.jpeg",
          text: "How to be a DJ? Make Electronic Music",
          genres: "Electronic",
        },
        {
          poster: "12345-1-370x200.png",
          text: "Nvidia and UE4 Technologies Practice",
          genres: "Nvidia",
        },
        {
          poster: "photo-1491897554428-130a60dd4757-370x200.jpeg",

          text: "Fashion Photography from professional",
          genres: "Fashion",
        },
        {
          poster: "photo-1416339134316-0e91dc9ded92-370x200.jpeg",

          text: "Design Instruments for Communication",
          genres: "Communication",
        },
        {
          poster: "cathryn-lavery-67852-unsplash-370x200.jpg",

          text: "Make your Concept Right and Beautiful",
          genres: "Art",
        },
        {
          poster: "photo-1475452779376-caebfb988090-370x200.jpeg",

          text: "Road Bike Manual or How to Be a Champion",
          genres: "Bicycling",
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
.cards-courses {
  background-color: #e1eef7;
  margin-top: 30px;
}

a {
  background-color: #f2b91e;
  padding: 10px 20px;
  color: white;
  text-decoration: none;
  border-radius: 50px;
}
</style>