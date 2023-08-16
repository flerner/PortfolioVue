<template>
  <div class="main-container">
    <div class="main-container_main-info">
      <div class="main-container_profile">
        <img src="../assets/profile-photo.jpg" alt="" />
        <h2>Félix Lerner</h2>
        <p>Software Developer</p>
      </div>
      <div class="main-container_social-links">
        <a href="https://www.linkedin.com/in/flerner/"
          ><i class="fab fa-linkedin"></i
        ></a>
        <a href="https://www.instagram.com/tocatuvue/"
          ><i class="fab fa-instagram"></i
        ></a>
        <a href="https://es-la.facebook.com/tocatu"
          ><i class="fab fa-facebook"></i
        ></a>
      </div>
    </div>
    <div class="main-container_about">
      <div class="main-container_about-me">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur
        dapibus feugiat velit eu auctor. Praesent metus quam, posuere non
        lacinia ut, molestie aliquam tellus. Integer et augue sapien. Quisque at
        orci sodales dolor consectetur condimentum. Ut semper fermentum mauris
        sed ornare. Nulla sed dictum turpis. Donec rhoncus est in dictum
        aliquam. Proin dapibus accumsan mauris, eget iaculis ipsum porttitor
        nec. Duis et cursus velit, vel volutpat odio. In arcu sem, congue id
        velit ut, tristique semper elit.
      </div>
      <div class="main-container_tecnologies">
        <h2>Tecnologies studied</h2>
        <p>asd</p>
        <br />
        <i class="fab fa-js"></i>
        <i class="fab fa-html5"></i>
        <i class="fa-brands fa-css3-alt"></i>
        <i class="fa-brands fa-vuejs"></i>
        <i class="fa-brands fa-node-js"></i>
      </div>
      <div class="main-container_projects">
        <h1>My projects</h1>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  mounted() {
    const script = document.createElement("script");
    script.src = "https://kit.fontawesome.com/81d70dbb2a.js";
    script.crossOrigin = "anonymous";
    document.body.appendChild(script);
  },
};
</script>

<style scoped>
img {
  width: 100%;
}
p {
  display: inline;
}
.main-container_social-links a i {
  font-size: 2em;
  color: blue;
}
.main-container_tecnologies i {
  font-size: 2em;
  color: green;
}
.main-container {
  display: flex;
  flex-direction: row;
  background-color: #9c9595;
  align-items: flex-start;
}
.main-container_main-info {
  padding: 20px;
  margin: 20px;
}
.main-container_about {
  margin: 20px;
}
</style>
