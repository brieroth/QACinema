<template>
  <body style="background-color: #2c3e50">
  <div class="hello">
    <head>
      <title>QA Cinema</title>
      <meta charset="utf-8">
      <meta name="viewport" content="width=device-width, initial-scale=1">
    </head>
        <navigation/>
    <div id="myCarousel" class="carousel slide" data-ride="carousel">
      <!-- Indicators -->
      <ol class="carousel-indicators">
        <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
        <li data-target="#myCarousel" data-slide-to="1"></li>
        <li data-target="#myCarousel" data-slide-to="2"></li>
      </ol>
      <!-- Wrapper for slides -->
      <div class="carousel-inner" role="listbox">
        <div class="item active">
          <img src="https://vignette.wikia.nocookie.net/xmenmovies/images/e/e9/Deadpool-film-header-front-main-stage.jpg/revision/latest?cb=20150805032419" alt="New York" width="100%" height="100px">
        </div>
        <div class="item">
          <img src="http://s3.foxmovies.com/foxmovies/production/films/132/images/feature/logan-film-header-front-main-stage.jpg" alt="Chicago" width="100%" height="100px">
        </div>
        <div class="item">
          <img src="http://www.twitrcovers.com/wp-content/uploads/2014/09/Godzilla-l.jpg" alt="Los Angeles" width="100%" height="100px">
        </div>
      </div>
      <!-- Left and right controls -->
      <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">
        <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
      </a>
      <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">
        <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
      </a>
    </div>
    <!-- columns -->
    <div class="row">
      <div class="column" style="background-color:#ccc">Column</div>
      <div class="column" style="background-color:#bbb;">Column</div>
      <div class="column" style="background-color:#ccc;">Column</div>
    </div>
    <!-- Container (Services Section) -->
    <div id="services" class="container-fluid text-center" style="background-color:#aaa">
      <h2>SERVICES</h2>
       <br>
      <div class="row slideanim" >
        <div class="col-sm-4">
          <span class="glyphicon glyphicon-eye-open"></span>
          <h4>Find Us</h4>
          <button type="button">Click Me!</button>
        </div>
        <div class="col-sm-4">
          <span class="glyphicon glyphicon-heart logo-small"></span>
          <h4>LOVE</h4>
          <p>Lorem ipsum dolor sit amet..</p>
        </div>
        <div class="col-sm-4">
          <span class="glyphicon glyphicon-lock logo-small"></span>
          <h4>JOB DONE</h4>
          <p>Lorem ipsum dolor sit amet..</p>
        </div>
      </div>
      <br><br>
      <div class="row slideanim">
        <div class="col-sm-4">
          <span class="glyphicon glyphicon-leaf logo-small"></span>
          <h4>GREEN</h4>
          <p>Lorem ipsum dolor sit amet..</p>
        </div>
        <div class="col-sm-4">
          <span class="glyphicon glyphicon-certificate logo-small"></span>
          <h4>CERTIFIED</h4>
          <p>Lorem ipsum dolor sit amet..</p>
        </div>
        <div class="col-sm-4">
          <span class="glyphicon glyphicon-wrench logo-small"></span>
          <h4 style="color:#303030;">HARD WORK</h4>
          <p>Lorem ipsum dolor sit amet..</p>
        </div>
      </div>
    </div>

  </div>
  </body>
</template>

<script>
import Navigation from './navigation'
import Footer from './footer'

export default {
  name: 'HelloWorld',
  components: {Navigation, Footer},
  data () {
    return {
    }
  }
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  {
    box-sizing: border-box;
  }

  body {
    font-family: Arial, Helvetica, sans-serif;
    /*background-image: url("../assets/maxresdefault.jpg");*/
    background-blend-mode: lighten;
  }
  /* Style the header */
  .header {
    background-color: #f1f1f1;
    padding: 30px;
    text-align: center;
    font-size: 35px;
  }

  /* Create three equal columns that floats next to each other */
  .column {
    float: left;
    width: 33.33%;
    padding: 10px;
    height: 300px; /* Should be removed. Only for demonstration */
  }

  /* Clear floats after the columns */
  .row:after {
    content: "";
    display: table;
    clear: both;
  }

  /* Style the footer */
  .footer {
    background-color: #f1f1f1;
    padding: 10px;
    text-align: center;
  }

  /* Responsive layout - makes the three columns stack on top of each other instead of next to each other */
  @media (max-width: 600px) {
    .column {
      width: 100%;
    }
  }
</style>
