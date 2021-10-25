<template>
  <div class="container-fluid bg-1 text-center" lang="en">
    <!-- Navbar -->
    <nav class="navbar navbar-default">
      <div class="container">
        <div class="collapse navbar-collapse" id="myNavbar">
          <ul class="nav navbar-nav navbar-top">
            <li><a href="#">WHO</a></li>
            <li><a href="#">WHAT</a></li>
            <li><a href="#">WHERE</a></li>
          </ul>
        </div>
      </div>
    </nav>

    <h1 class="margin">{{ title }}</h1>
    <img
      src="bird.jpg"
      class="img-responsive img-circle margin"
      style="display: inline"
      alt="Bird"
      width="350"
      height="350"
    />
    <h3>{{ description }}</h3>
    
    <div class="container-fluid bg-3 text-center">
      <h3 class="margin">Where To Find Me?</h3>
      <br />
      <div class="row">
        <div class="col-sm-4">
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua.
          </p>
          <img
            src="birds1.jpg"
            class="img-responsive margin"
            style="width: 100%"
            alt="Image"
          />
        </div>
        <div class="col-sm-4">
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua.
          </p>
          <img
            src="birds2.jpg"
            class="img-responsive margin"
            style="width: 100%"
            alt="Image"
          />
        </div>
        <div class="col-sm-4">
          <p>
            Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua.
          </p>
          <img
            src="birds3.jpg"
            class="img-responsive margin"
            style="width: 100%"
            alt="Image"
          />
        </div>
      </div>
    </div>

    <footer class="container-fluid bg-4 text-center">
      <h2>Redes sociais</h2>
      <p>
        Bootstrap Theme Made By
        <a href="https://www.w3schools.com">www.portifoliomilene.com</a>
      </p>
      <li>
        <a href="https://www.linkedin.com/in/milene-martins/" target="_blank">
          <img
            src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white"
            target="_blank"
        /></a>
      </li>
      <li>
        <a href="mailto:mileneapmartins@gmail.com">
          <img
            src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white"
            target="_blank"
        /></a>
      </li>
      <li>
        <a href="https://www.instagram.com/mi_apm/" target="_blank">
          <img
            src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white"
            target="_blank"
        /></a>
      </li>
      <li>
        <a href="https://github.com/Mileneapm" target="_blank">
          <img
            src="https://img.shields.io/github/followers/Mileneapm?style=social"
            target="_blank"
        /></a>
      </li>
    </footer>
  </div>
</template>

<script>
export default {
  name: "app",
  data() {
    return {
      title: "Blog Portfólio Milene Martins",
      description: "Blog para divulgar meu trabalho",
    };
  },
};
</script>

<style>
#container-fluid {
  padding-top: 60px;
  padding-bottom: 70px;
  justify-content: center;
  align-items: center;
}

body {
  font: 20px Montserrat, sans-serif;
  line-height: 1.8;
  color: #d1dfe6;
}
p {
  font-size: 16px;
}

.margin {
  margin-bottom: 45px;
}
.bg-1 {
  background-color: #050e0c; /* Green */
  color: #ffffff;
}
.bg-2 {
  background-color: #474e5d; /* Dark Blue */
  color: #ffffff;
}
.bg-3 {
  background-color: #ffffff; /* White */
  color: #555555;
}
.bg-4 {
  background-color: #2f2f2f; /* Black Gray */
  color: #fff;
}
.container-fluid {
  padding-top: 70px;
  padding-bottom: 70px;
}
.navbar {
  padding-top: 15px;
  padding-bottom: 15px;
  border: 0;
  border-radius: 0;
  margin-bottom: 0;
  font-size: 12px;
  letter-spacing: 5px;
}
.navbar-nav li a:hover {
  color: #1abc9c !important;
}

h1,
h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}
</style>
