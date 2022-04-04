<template> 
    <div class="Blog">
        <div class="container">
          <h1>{{title}}</h1>
          <h1>{{divider1}}</h1>
          
          <h5>{{hobby1}}</h5>
          <br>
          <h5>{{desc1}}</h5>
          <br>
          <h5>{{divider}}</h5>
          <br>
          <h5>{{hobby2}}</h5>
          <br>
          <h5>{{desc2}}</h5>
          <br>
          <h5>{{divider}}</h5>
          <br>
          <h5>{{hobby3}}</h5>
          <br>
          <h5>{{desc3}}</h5>
          <br>
          <br>
          <h1>{{divider1}}</h1>
    </div>
    </div> 
</template> 
<script> 
    export default { 
            name: 'Blog', 
            data () { 
                return{ 
                    title: 'Personal Hobbies',
                    hobby1: 'Reading Educational Websites',
                    hobby2: 'Watching Videos Related to my Future Profession',
                    hobby3: 'Procastinating After Finishing all my works',

                    desc1: 'Reading site that are not even realated to my future profession gives my a motivation on why should I study harder, that I dont know much things and should continue learning.',
                    desc2: 'Watching HTML,JS,CSS,MySql and Vue tutorial provides a background knowledge for my, I consider this as my Advance reading in my subjects. Knowing more for me is better than limiting my self. This is also to improved my designing skills in CSS and other programming languages.',
                    desc3: 'This is a bad habit of mine where If I finish my task for a whole week I will start to procastinate. Needing a momentum when doing my schoolworks. This is the reason why I hate breaks if we are in the middle of the semester.',

                    divider: '---------------------------------------------------------------',
                    divider1: '---------------------------'
                }
            }
    }
</script>

<style>

</style>