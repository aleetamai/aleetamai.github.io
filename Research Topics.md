

<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>


<!-- DEFINE THE STYLE OF THE WEBSITE MENU  -->


<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu Example</title>
    <style>
        /* Optional: Some basic styling for demonstration */
        .menu-container {
            text-align: center; /* Center the menu */
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: inline-block; /* Make the menu display inline-block */
        }
        nav li {
            display: inline;
            margin-right: 10px;
        }
        nav a {
            text-decoration: none;
            color: #000; /* Black text color */
            font-weight: bold;
            font-size: 20px; 
        }
    </style>
</head>
<body>

<div class="menu-container">
    <nav>
        <ul>
            <li><a href="https://aleetamai.github.io">Home</a></li>
            <li><a href="https://aleetamai.github.io/talks&carrer">Talks&Career</a></li>
            <li><a href="https://aleetamai.github.io/works">Works</a></li>
            <li><a href="https://aleetamai.github.io/Research Topics">Research Topics</a></li>
        </ul>
    </nav>
</div>
</body>


<!-- MAIN  -->

# Statistical Learning 
## Machine Learning
## Manifold Hypothesis

Implicit regression models can be seen as generalizations of classical explicit regression methods from classical statistics (see \Cref{sec:Regression Analysis}). Informally, we are given a set of points $x^1,\dots , x^m$ sampled by a random vector $X$ with values in $\R^n$ that corresponds to a Borel measure $\mu$ compactly supported on $D_R^n$. The goal is to find a system of equations that $X$ approximately satisfies. If we restrict to the regular systems, that is if the gradients of the equations are independent, a local explicit relation between the components of $X$ is guaranteed, and the problem can be conceptually traced back to the classical problem of explicit regression (see \Cref{sec:WCSystems}).

This explicit relations are consequence of the fact that, with such conditions, the set of solutions is a smooth submanifold of $\R^n$  (see  \Cref{sec:WCSystems}). This relates the problem to the manifold hypothesis problem in manifold learning  in the formulation of [fefferman], once the hypothesis class considered is the one of manifolds with trivial normal bundle (see \Cref{sec:Algebraic Complete Intersections}), and relates with our previous work [cita nostro paper]. Informally, manifolds hypothesis asserts that collected data actually concentrates near a lower dimensional manifold of the ambient space. In term of testing this  hypothesis in the spirit of [fefferman] different classes of manifolds can be considered. Each of these choices corresponds, from the statistical point of view, to the choice of an hypothesis class for the hypothesis test. More formally, we say that the random vector $X$ satisfies the $\varepsilon$-manifold hypothesis in a hypothesis class $\mathcal{H}$ if there exists a manifold $Z \in \mathcal{H}$ such that $\E[\dist(X,Z)^2] <\varepsilon$. An illustration of the problem setting is given by \Cref{fig:manifold}.



# Morse Theory
<p>
Given a smooth real manifold \(M\) and a smooth function \(f: M \rightarrow \mathbb{R}\), at any critical point $x$ of $f$, the notion of the _Hessian matrix_ of \(f\) at \(x\) is well-defined. If, at every critical point, this matrix is invertible, then \(f\) is called a _Morse function_.

Since the Hessian is symmetric, at each critical point we can associate the number of negative eigenvalues of this matrix; this number is called the _index_ of the critical point.

It turns out that the class of Morse functions on a manifold is strongly related to the topology of the manifold itself: for any \(f\), the \(k\)-th Betti number of \(M\) is bounded above by the number of critical points of \(f\) of index \(k\). This is the so-called (weak) _Morse inequality_. Moreover, the function defines a way of decomposing \(M\), by gluing together different _handles_, giving rise to a so called _handle decomposition_ of \(M\).

The applications of this theory are numerous: on one hand, finding "minimal" Morse functions on a manifold helps to describe its topology; on the other hand, critical points of functions (and more generally, of functionals) play a central role in optimization problems, dynamical systems, and beyond. Counting these critical points provides a notion of the _complexity_ of the associated problem.
</p>

# Lie Algebras and Groups

<p>
  When \(a \ne 0\), there are two solutions to \(ax^2 + bx + c = 0\) and they are
  \[x = {-b \pm \sqrt{b^2-4ac} \over 2a}.\]



$$x^2+\int_{0}^1f(x)dx$$
