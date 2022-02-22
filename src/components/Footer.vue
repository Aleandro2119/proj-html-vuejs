<template>
  <footer class="mt-5 pt-5">
    <div class="container">
      <div class="row">
        <div class="col-3">
          <h4>ABOUT</h4>
          <ul>
            <li
              class="list-unstyled"
              v-for="(about, index) in abouts"
              :key="index"
            >
              <a :href="about.url">{{ about.text }}</a>
            </li>
            <i class="fa-brands fa-facebook"></i>
            <i class="fa-brands fa-twitter p-4"></i>
            <i class="fa-brands fa-instagram"></i>
          </ul>
        </div>
        <div class="col-3">
          <h4>CONTACT</h4>
          <ul>
            <li
              class="list-unstyled"
              v-for="(contact, index) in contacts"
              :key="index"
            >
              <a :href="contact.url">{{ contact.text }}</a>
            </li>
          </ul>
        </div>
        <div class="col-3">
          <h4>PAGES</h4>
          <ul>
            <li v-for="(page, index) in pages" :key="index">
              <a :href="page.url">{{ page.text }}</a>
            </li>
          </ul>
        </div>
        <div class="col-3">
          <h4>BLOG</h4>

          <ul>
            <li
              class="list-unstyled"
              v-for="(blog, index) in blogs"
              :key="index"
            >
              <img :src="require(`../assets/img/${blog.image}`)" alt="" />
              <a class="text-black fw-bold" :href="blog.url">{{ blog.text }}</a>
              <span>{{ blog.date }}</span>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer",

  data() {
    return {
      abouts: [
        { text: "Masterstudy is Education WordPress", url: "#" },
        { text: "theme featured by Learning", url: "#" },
        { text: "Management System (LMS) for online", url: "#" },
        { text: "education", url: "#" },
        { text: "Developed by Stylemix Themes.", url: "#" },
      ],

      contacts: [
        { text: "USA, Callifornia 20, First Avenue, Callifornia", url: "#" },
        { text: "", url: "#" },
        { text: "Tel.: +1 212 458 300 32", url: "#" },
        { text: "Fax: +1 212 375 24 14", url: "#" },
        { text: "", url: "#" },
        { text: "info@masterstudy.com", url: "#" },
      ],

      pages: [
        { text: "Blog", url: "#" },
        { text: "Home", url: "#" },
        { text: "Shortcodes", url: "#" },
        { text: "Courses", url: "#" },
        { text: "Membership A...", url: "#" },
        { text: "Typography", url: "#" },
      ],

      blogs: [
        {
          image: "photo-1517520287167-4bbf64a00d66-69x69.jpeg",
          text: "Our main target is to 'Developing Yourself as a Leader' ",
          date: "-August 9, 2018",
          url: "#",
        },
        {
          image: "photo-1490376840453-5f616fbebe5b-69x69.jpeg",
          text: "MAD Magazine",
          date: "-June 3, 2015",
          url: "#",
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
footer {
  background-color: #f2b91e;
  ul {
    padding: 0;

    a,
    span {
      text-decoration: none;
      color: #4d5156;
    }
  }
}
</style>