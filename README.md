<!DOCTYPE html>
<html>
  <head>
    <script src="https://unpkg.com/ml5@0.4.3/dist/ml5.min.js"></script>
    
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/js/bootstrap.min.js"></script>
    
    <title>p5.play.Mario</title>
    <!-- link p5.js and its addons like p5.dom.js or p5.sound.js -->
    <script src="lib/p5.min.js" type="text/javascript"></script>
    <!-- link p5.play.js -->
    <script src="lib/p5.play.js" type="text/javascript"></script>
    <!-- link p5.dom.js -->
    <script src="lib/p5.dom.js" type="text/javascript"></script>

    <!-- link your javascript sketch -->
    <script src="scripts/sprites.js" type="text/javascript"></script>

    <script src="main.js" type="text/javascript"></script>

    <script src="characters_environment.js" type="text/javascript"></script>

    <link rel="stylesheet" type="text/css" href="style.css">
    
    <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.0.0/addons/p5.sound.min.js"></script>

  </head>
  <body background="background.jpg">
<center>
  <div class="btn btn-info heading">
    <h3>AI Mario Game </h3>
    
    <button class="btn btn-primary" data-toggle="modal" data-target="#mymodal">Instruction</button>

  </div>
  <img src="mario.jpg " class="big_image">
  <br>
  <br>
  <button onclick="start()"class="btn btn-success " id="start_btn">Play Game </button>
  <br>
  <br>
  
  <h3 id="status" class="btn btn-danger"></h3>
  <br>
  <br>
  <div id="canvas"></div>
  
  <div id="game_console"></div>

  <h4 >Source Code <a href="https://github.com/linuk">linuk</a> || Game Credit: Mario</h4>
  
  <div id="mymodal" class="modal fade">
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-header">
          <button class="close" data-dismiss="modal">&times;</button>
          <h4 >Instruction</h4>
        </div>
        <div class="modal-body">
          <img src="jump.png" class="img-responsive inst">
          <img src="left.png" class="img-responsive inst">
          <img src="right.png" class="img-responsive inst ">

        </div>
      </div>
    </div>
  </div>
</center>
  </body>
</html>
