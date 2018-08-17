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
        <router-link to="/avengers"><a href="ListingsGallery.vue"><img src="https://terrigen-cdn-dev.marvel.com/content/prod/1x/avengersinfinitywar_lob_crd_02.jpg" alt="Avengers Infinity War" width="400" height="500" align="center"></a></router-link>
        <a href="/johnwick"><img src="https://m.media-amazon.com/images/M/MV5BMTU2NjA1ODgzMF5BMl5BanBnXkFtZTgwMTM2MTI4MjE@._V1_.jpg" alt="John Wick" width="400" height="500" align="center"></a>
        <a href="/transformers"><img src="https://m.media-amazon.com/images/M/MV5BNDg1NTU2OWEtM2UzYi00ZWRmLWEwMTktZWNjYWQ1NWM1OThjXkEyXkFqcGdeQXVyMTQxNzMzNDI@._V1_.jpg" alt="Transformers" width="400" height="500" align="center"></a>
        <a href="/transporter"><img src="https://is2-ssl.mzstatic.com/image/thumb/Music1/v4/26/86/d5/2686d55e-02b4-7a4a-7354-89c5999d8122/3700551779512_cover.jpg/600x600bf.jpg" alt="The Transporter" width="400" height="500" align="center"></a>
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
