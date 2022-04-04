<template>
  <div class="Education">
    <title>{{title}}</title>
    <h1>{{ msg }}</h1>
    <div class="container">
          <h1>Educational Background</h1>
          <br>
          <br>
          <h5>{{elem}}</h5>
          <h5>{{school1}}</h5>
          <br>
          <h5>{{divider}}</h5>
          <br>
          <h5>{{jhs}}</h5>
          <h5>{{school2}}</h5>
          <br>
          <h5>{{divider}}</h5>
          <br>
          <h5>{{shs}}</h5>
          <h5>{{school2}}</h5>
          <br>
          <h5>{{divider}}</h5>
          <br>
          <h5>{{cllg}}</h5>
          <h1>{{crs}}</h1>
          <h5>{{school2}}</h5>
    </div>
  </div>
  
</template>

<script>
export default {
  name: 'Education',
  data () {
    return {
      title: 'Education',
      elem: 'Elementary School (Kinder to Grade 6)',
      school1: 'Humprey Foundation Learning Center.',
      school2: 'Holy Angel University',
      jhs: 'Junior Highschool (Grade 7- 10)',
      shs: 'Senior Highschool (Grade 11-12)',
      cllg: '1st and 2nd Year College',
      crs: 'BSIT - Web Dev',
     
      divider: '---------------------------------------------------------------'
    }
  }
}
</script>


<style scoped>

</style>