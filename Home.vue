<template>
  <div class="Home">
    <title>{{title}}</title>
    
    <div class="container">
          <div class="container-img"></div>
          <h1>Magbanua Karl Caniel D</h1>
          <h5>Information Technology - Web Developer</h5>
          <br>
          <p>{{p}} <br> <br> {{p2}}</p>
          <br>
          <br>
          <p>{{Note}}</p>
        </div>
  </div>
</template>

<script>



export default {
  name: 'Home',
  data () {
    return {
      
      
      p: 'This Website shows my current knowledge on vue.js css and html',
      p2: 'The website will be a practice for Vuejs css and html coding of mine. The following route Educationn, Blogm About Me and Contact will be my personal information',
      Note: 'Note: This page is minimalist and simple in design cause im trying to experiment on different code of Vue.js',
      
    }
    
  }
}
</script>


<style scoped>

</style>
