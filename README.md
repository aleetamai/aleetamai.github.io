

<div id="image-table" align="center">
    <table>
        <tr>
        <div class="topnav">
        <a href="https://aleetamai.github.io">Home</a>
        <a href="https://aleetamai.github.io/talks&carrer">Talks & Career</a>
        <a href="https://www.sissa.it">SISSA</a>
        </div>
        </tr>
    </table>
</div>

# Alessandro Tamai

<br>

<img align="left" width="520" src="assets/Lie_groups2.png" />


<img src="assets/sissalogo.png" width="130" />

-------

   ​_Ph.D. student at [SISSA](https://math.sissa.it/users/alessandro-tamai) in Geometry and Mathematical Physics, under the supervision of Antonio Lerario._

<br>

<br>
<br>
<br>
<br>

<div id="container" style="width:100%;">                                   
  <div id="left" style="float:left; width:50%;">
    <h2>Research Interests:</h2>
    My main research interest are on metric geometry,real algebraic geometry and Morse theory for data analysis and machine learning.        <br>     
    Other interests cover differential topology, Riemannian and subRiemannian geometry and Lie groups.
  </div>                     
  <div id="right" style="float:right; width:50%;">
      <h2>Contacts</h2>
      email:  atamai@sissa.it
      <br>
      office: room 416, SISSA, Via Bonomea, 265, 34136, Trieste (TS)
  </div>                   
</div> 






<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial;
}

/* The grid: Four equal columns that floats next to each other */
.column {
  float: left;
  width: 25%;
  padding: 10px;
}

/* Style the images inside the grid */
.column img {
  opacity: 0.8; 
  cursor: pointer; 
}

.column img:hover {
  opacity: 1;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* The expanding image container */
.container {
  position: relative;
  display: none;
}

/* Expanding image text */
#imgtext {
  position: absolute;
  bottom: 15px;
  left: 15px;
  color: white;
  font-size: 20px;
}

/* Closable button inside the expanded image */
.closebtn {
  position: absolute;
  top: 10px;
  right: 15px;
  color: white;
  font-size: 35px;
  cursor: pointer;
}
</style>
</head>
<body>

<div style="text-align:center">
  <h2>Tabbed Image Gallery</h2>
  <p>Click on the images below:</p>
</div>

<!-- The four columns -->
<div class="row">
  <div class="column">
    <img src="img_nature.jpg" alt="Nature" style="width:100%" onclick="myFunction(this);">
  </div>
  <div class="column">
    <img src="img_snow.jpg" alt="Snow" style="width:100%" onclick="myFunction(this);">
  </div>
  <div class="column">
    <img src="img_mountains.jpg" alt="Mountains" style="width:100%" onclick="myFunction(this);">
  </div>
  <div class="column">
    <img src="img_lights.jpg" alt="Lights" style="width:100%" onclick="myFunction(this);">
  </div>
</div>

<div class="container">
  <span onclick="this.parentElement.style.display='none'" class="closebtn">&times;</span>
  <img id="expandedImg" style="width:100%">
  <div id="imgtext"></div>
</div>

<script>
function myFunction(imgs) {
  var expandImg = document.getElementById("expandedImg");
  var imgText = document.getElementById("imgtext");
  expandImg.src = imgs.src;
  imgText.innerHTML = imgs.alt;
  expandImg.parentElement.style.display = "block";
}
</script>

</body>
</html>







