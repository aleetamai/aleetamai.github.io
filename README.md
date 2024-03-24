<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Left and Right Sidebands Example</title>
<style>
    /* Basic styling */
    body {
        margin: -100;
        padding: 0;
        font-family: Arial, sans-serif;
    }
    .container {
        position: relative;
        min-height: 100vh;
        overflow: hidden;
    }
    .left-band, .right-band {
        position: absolute;
        top: 0;
        bottom: 0;
        width: 200px; /* Adjust width as needed */
        background-color: #f0f0f0;
        padding: 20px;
        z-index: 1; /* Ensure it's behind the content */
    }
    .left-band {
        left: 0;
    }
    .right-band {
        right: 0;
    }
    .content {
        position: relative;
        z-index: 2; /* Ensure it's above the bands */
        padding: 20px;
    }
</style>
</head>
<body>

<div class="container">
    <!-- Left Band -->
    <div class="left-band">
        <h2>Left Band</h2>
        <p>This is the content of the left band.</p>
    </div>

    <!-- Right Band -->
    <div class="right-band">
        <h2>Right Band</h2>
        <p>This is the content of the right band.</p>
    </div>

    <!-- Page Content -->
    <div class="content">
        <h1>Main Content</h1>
        <p>This is the main content of your webpage.</p>
    </div>
</div>

</body>


<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Side Bar Example</title>
<style>
    /* Basic styling */
    body {
        margin: 0;
        padding: 0;
        font-family: Arial, sans-serif;
    }
    .container {
        display: flex;
    }
    .sidebar {
        width: 250px; /* Adjust width as needed */
        background-color: #f0f0f0;
        padding: 20px;
    }
    .content {
        flex: 1;
        padding: 20px;
    }
</style>
</head>



<!-- WEBSITE MENU  -->
    
<div id="image-table" align="center">
    <table>
        <tr>
        <div class="topnav">
        <a href="https://aleetamai.github.io">Home</a>
        <a href="https://aleetamai.github.io/talks&carrer">Talks & Career</a>
        <a href="https://aleetamai.github.io/works">Works</a>
        </div>
        </tr>
    </table>
</div>

<!-- TITLE AND PRESENTATION  -->

<h1>Alessandro Tamai</h1>


<br>

<img align="left" width="520" src="assets/Lie_groups2.png" />


<img src="assets/sissalogo.png" width="130" />

-------

​_Ph.D. student [at SISSA](https://math.sissa.it/users/alessandro-tamai) in Geometry and Mathematical Physics, under the supervision of Antonio Lerario._

<br>
<br>
<br>
<br>
<br>

<!-- CONTACTS AND INTERESTS  -->

<div class="container">
    <!-- Sidebar -->
    <div class="sidebar">
    <h2>Contacts</h2>
      <p>email:  atamai@sissa.it
      <br>
      office: room 416</p>
    </div>
    <!-- Page Content -->
    <div class="content">
    <h2>Research Interests:</h2>
     <p>My main interests are on applicatioons of metric geometry, real algebraic geometry and Morse theory in machine learning.                <br>     
    Other interests cover differential topology, Riemannian and subRiemannian geometry and Lie groups.</p>
    </div>
</div>

<!-- SISSA PHOTOS  -->

<br>

<h2>Sissa Buildings</h2>
 


<img align="left" width="440" src="assets/sissa-building10.jpg" />

<img align="right" width="440" src="assets/sissa2.jpg" />










