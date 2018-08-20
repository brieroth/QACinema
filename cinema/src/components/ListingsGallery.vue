<template>
  <div class="hello">
    <body style="background-color:transparent;">
    <head>
      <title>QA Cinema</title>
      <meta charset="utf-8">
      <meta name="viewport" content="width=device-width, initial-scale=1">
    </head>
    <navigation/>
      <h1 style="font-family:Verdana;">Currently Showing...</h1><br>
    <div class="responsive" align="center">
      <div class="gallery">
        <router-link to="/avengers"><a href="ListingsGallery.vue"><img src="../assets/avengers.jpg" alt="Avengers Infinity War" width="400" height="500" align="center"></a></router-link>
        <a href="/johnwick"><img src="../assets/johnwick.jpg" alt="John Wick" width="400" height="500" align="center"></a>
        <a href="/transformers"><img src="../assets/transformers.jpg" alt="Transformers" width="400" height="500" align="center"></a>
        <a href="/transporter"><img src="../assets/transporter.jpg" alt="The Transporter" width="400" height="500" align="center"></a>
      </div>
    </div>
    <div>
      <div class="column">
        <h2>Column</h2>
        <p>Avengers</p>
    </div>
    </div>
    </body>
  </div>
</template>

<script>
import Navigation from './navigation'
import footer from './footer'
import avengers from './avengers'
export default {
  name: 'ListingsGallery',
  components: {Navigation, avengers, footer},
  data () {
    return {
    }
  }
}
</script>

<style scoped>

</style>
