<template>
  <header>
  <div id="app">
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">VueJs</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarColor02" aria-controls="navbarColor02" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarColor02">
      <ul class="navbar-nav me-auto">
        <li class="nav-item">
          <!----->
          <router-link class="nav-link" to="/Home">Home</router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link" to="/Blog">Hobbies</router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link" to="/Education">Education</router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link" to="/AboutMe">About Me</router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link" to="/Contact">Contact</router-link>
        </li>

        
        
        <!----->
      </ul>
    </div>
  </div>
</nav>
    <router-view/>
  </div>
  </header>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
body{
  margin: 0;
  margin-left: 5px;
  margin-right: px;
  padding: 0;
  background: url(./assets/background.jpg) no-repeat;
  background-size: cover;
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  font-weight: inherit;
  line-height: 1.2em;
  list-style: none;
  text-decoration: none;
  vertical-align: baseline;
}
/**********Home.vue**********/
.container {
  width: 550px;
  background: rgba(0, 0, 0, 0.4);
  padding: 40px;
  text-align: center;
  margin: auto;
  margin-top: 5%;
  color: whitesmoke;
  font-family: Arial, Helvetica, sans-serif;
}

.container-img {
  border-radius: 50%;
  width: 200px;
  height: 200px;

}

.container h1 {
  font-size: 40px;
  letter-spacing: 4px;
  font-weight: 100;
}

.container h2 {
  font-size: 20px;
  letter-spacing: 3px;
  font-weight: 100;

}

.container p {
  text-align: justify;
}

</style>
