<template>
  <div class="AboutMe">
    
     <div class="container">
          <h1>{{title}}</h1>
          <h1>{{divider1}}</h1>
          
          <h5>{{fave}}</h5>
          <br>
          <h5>{{fave1}}<br> {{fave2}} <br> {{fave3}} </h5>
          <br>
          <h5>{{divider}}</h5>
          <br>
          <h5>{{atti}}</h5>
          <br>
          <h5>{{atti1}}<br> {{atti2}} <br> {{atti3}}</h5>
          <br>
          <h5>{{divider}}</h5>
          <br>
          <h5>{{char}}</h5>
          <br>
          <h5>{{char1}}<br> {{char2}} <br> {{char3}}</h5>
          <br>
          <br>
          <h1>{{divider1}}</h1>
    </div>
  </div>
</template>

<script>
export default {
  name: 'AboutMe',
  data () {
    return {
      title: 'About Me',
      fave: 'Favorites',
      atti: 'Attitude',
      char: 'Characteristic',

      fave1: '> Food: Sisig',
      fave2: '> Place: Home',
      fave3: '> Activity: Sleeping',

      atti1: '> Independent',
      atti2: '> Hardworking',
      atti3: '> Grateful',

      char1: '> Honest',
      char2: '> Fairness',
      char3: '> Responsible',

      divider: '---------------------------------------------------------------',
      divider1: '---------------------------'
    }
  }
}
</script>


<style>

</style>