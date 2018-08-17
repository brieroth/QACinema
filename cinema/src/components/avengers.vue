<template>
  <body>
  <navigation/>
  <div class="gallery" align="center">
    <h1>Avengers Infinity War (2018)</h1>
    <p>The Movie Currently Showing</p>
      <img src="https://terrigen-cdn-dev.marvel.com/content/prod/1x/avengersinfinitywar_lob_crd_02.jpg" alt="Avengers Infinity War" width="400" height="500" align="center">
    <p>Title: Avengers Infinity War</p>
    <p>Actors:<i>Robert Downey Jr, Benedict Cumberbatch, Chris Pratt, Chris Hemsworth, Scarlett Johansson, Tom Holland, Chris Evans, Elizabeth Olsen, Sebastian Stan, Tom Hiddleston, Mark Ruffalo, Chadwick Boseman, Josh Brolin, Anthony Mackie, Paul Bettany, Zoe Saldana, Dave Bautista, Karen Gillan, Don Cheadle, Pom Klementieff, Danai Gurira</i> </p>
    <p>Directors:<i>Anthony Russo, Joe Russo</i></p>
    <p>Showing Times:<i><tr>2:45pm</tr> <tr>6:25pm</tr> <tr>9:45pm</tr></i></p>
  </div>
  </body>
</template>

<script>
import Navigation from './navigation'
export default {
  name: 'avengers',
  components: {Navigation},
  data () {
    return {
    }
  }
}
</script>
 <style scoped>
</style>
