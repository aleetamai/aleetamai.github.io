
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Alessandro Tamai</title>
    <style>
        /* --- Menu Style --- */
        .menu-container {
            text-align: center;
            margin-bottom: 20px;
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: inline-block;
        }
        nav li {
            display: inline;
            margin-right: 10px;
        }
        nav a {
            text-decoration: none;
            color: #000;
            font-weight: bold;
            font-size: 20px;
        }

        /* --- Responsive Columns --- */
        * {
            box-sizing: border-box;
        }

        .row {
            display: flex;
            flex-wrap: wrap;
            margin: 0 -10px;
        }

        .column {
            padding: 10px;
        }

        .left {
            flex: 1 1 100%;
            max-width: 100%;
        }

        .right {
            flex: 1 1 100%;
            max-width: 100%;
        }

        @media (min-width: 768px) {
            .left {
                flex: 1 1 25%;
                max-width: 25%;
            }

            .right {
                flex: 1 1 75%;
                max-width: 75%;
            }
        }
    </style>
</head>
<body>

<!-- Menu -->
<div class="menu-container">
    <nav>
        <ul>
            <li><a href="https://aleetamai.github.io">Home</a></li>
            <li><a href="https://aleetamai.github.io/talks&carrer">Talks&Career</a></li>
            <li><a href="https://aleetamai.github.io/works">Works</a></li>
        </ul>
    </nav>
</div>

<!-- Titolo e Introduzione -->
<h1>Alessandro Tamai</h1>

<br>

<img align="left" width="520" src="assets/myfoto2" alt="My photo" />
<img src="assets/sissalogo.png" width="130" alt="SISSA logo" />
<br>
<p>
    <em>Ph.D. student 
    <a style="color:black;" href="https://math.sissa.it/users/alessandro-tamai"><b>at SISSA</b></a> 
    in Geometry and Mathematical Physics as member of the 
    <a style="color:black;" href="https://sites.google.com/view/realalgebraicgeometry/home"><b>Real Geometry Group</b></a>, 
    under the supervision of 
    <a style="color:black;" href="https://sites.google.com/view/lerario/home"><b>Antonio Lerario</b></a>.
    </em>
</p>

<!-- Contatti e Interessi -->
<div class="row">
    <div class="column left" style="background-color:white;">
        <h2>Contacts</h2>
        <p>
            email: atamai@sissa.it<br>
            office: room 416
        </p>
    </div>

    <div class="column right" style="background-color:white;">
        <h2 style="color:black;">Research Interests:</h2>
        <p style="color:black;">
            My main interests are on applications of metric geometry, real algebraic geometry and Morse Theory in machine learning.
            Other interests cover differential topology, Riemannian and subRiemannian geometry and Lie groups.
        </p>
    </div>
</div>

<!-- Dove mi trovo -->
<div class="row">
    <div class="column right" style="background-color:white;">
        <h2 style="color:black;">Where I am (right now):</h2>
        <p style="color:black;">
            SISSA is a beautiful research center in Trieste (Italy), surrounded by mountains and sea, wrapped in the wind.
        </p>
    </div>
</div>

<!-- Immagini -->
<figure style="text-align: center;">
    <img src="assets/Sfondo.jpg" width="440" alt="SISSA View" />
    <img src="assets/sissa-building10.jpg" width="440" alt="SISSA Building" />
    <figcaption>
        The beautiful view from one of SISSA’s terraces on the left. SISSA building on the right.
    </figcaption>
</figure>

</body>
</html>



