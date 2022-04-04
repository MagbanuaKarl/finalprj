<template>
  <div class="Contact">
    <div class="container">
          <h1>{{title}}</h1>
          <h1>{{divider1}}</h1>
          <br>
          <br>
          <h1>Email:</h1>
          <h5>{{eml}}</h5>
          <br>
          <h5>{{divider}}</h5>
          <br>
          <h1>Phone Number</h1>
          <h5>{{pn}}</h5>
          <br>
          <h5>{{divider}}</h5>
          <br>
          <h1>Facebook</h1>
          <h5>{{fb}}</h5>
          <br>
          <h5>{{divider}}</h5>
          <br>
        </div>  
  </div>
</template>

<script>
export default {
  name: 'Contact',
  data () {
    return {
      title: 'Contact Information',
      eml: 'karlcaniel23@gmail.com',
      pn: '+63 917 609 5210',
      fb: 'Karl Magbanua',
      divider: '---------------------------------------------------------------',
      divider1: '---------------------------'

    }
  }
}
</script>


<style>

</style>
