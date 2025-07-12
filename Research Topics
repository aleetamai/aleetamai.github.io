

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

# Machine Learning

## Statistical Inference 
<p style="text-align: justify;">
What is statistical inference? Statistical inference is, in a sense, the inverse procedure of probability. In probability theory, we consider a random variable whose probability distribution we study, and from which we can generate data. In statistical inference, on the other hand, we start from observed data and aim to reconstruct (i.e., infer) the probability distribution that generated them.

Consider, for example, a herd of 1,000 elephants, of which some are known to be female and others male. If we randomly select 100 of these elephants and count how many are male and how many are female, can we determine the composition of males and females in the entire herd? This is, in a sense, the central question of statistics. The procedure used to answer this question is generally referred to as inference. As one might expect, it is not possible to provide an exact answer to the question, but it is possible to quantify the probability that the answer is correct and to control this probability. Suppose we have two mutually exclusive hypotheses, \(H_0\) and $H_1$. How can we quantify which of the two is inconsistent with the data? Assume that we observe data \(D=\left\{x_1, \ldots, x_k\right\}\) and choose a model \(M(\theta)\), that is, we assume the data are distributed as \[M(\theta): x_i \sim X_M(\theta)\] where the distribution depends on the parameters $\theta$ (for example, if the model \(M\) is Gaussian, the parameters would be its mean and variance). If we consider the null hypothesis \(H_0\), which states that the true parameter is \(\theta_0\), and the alternative hypothesis \(H_1\), which states that the true parameter is \(\theta_1\), we can write

\[
\begin{aligned}
& H_0: M\left(\theta_0\right)=M_0 \quad \Longleftrightarrow \quad x_i \sim X_M\left(\theta_0\right)=X_0 \\
& H_1: M\left(\theta_1\right)=M_1 \quad \Longleftrightarrow \quad x_i \sim X_M\left(\theta_1\right)=X_1
\end{aligned}
\] To discriminate quantitatively between the two models, we can employ a test statistic, which is a function \(T\) of the random variable \(X(\theta)\), whose probability distribution does not depend on \(\theta\); that is, \(t(x(\theta))=t(x)\)


Thus, the function \(T\) depends on the data, but its probability distribution does not. Can a such kind of function exists? Well, the answer is yes, and it is the reason why the Central Limit Theorem is the cornestone of probability theory:

</p>

## Statistical Learning 
## The Manifold Hypothesis
<p style="text-align: justify;">
Implicit regression models can be seen as generalizations of classical explicit regression methods from classical statistics (see \Cref{sec:Regression Analysis}). Informally, we are given a set of points $x^1,\dots , x^m$ sampled by a random vector $X$ with values in $\R^n$ that corresponds to a Borel measure $\mu$ compactly supported on $D_R^n$. The goal is to find a system of equations that $X$ approximately satisfies. If we restrict to the regular systems, that is if the gradients of the equations are independent, a local explicit relation between the components of $X$ is guaranteed, and the problem can be conceptually traced back to the classical problem of explicit regression (see \Cref{sec:WCSystems}).

This explicit relations are consequence of the fact that, with such conditions, the set of solutions is a smooth submanifold of $\R^n$  (see  \Cref{sec:WCSystems}). This relates the problem to the manifold hypothesis problem in manifold learning  in the formulation of [fefferman], once the hypothesis class considered is the one of manifolds with trivial normal bundle (see \Cref{sec:Algebraic Complete Intersections}), and relates with our previous work [cita nostro paper]. Informally, manifolds hypothesis asserts that collected data actually concentrates near a lower dimensional manifold of the ambient space. In term of testing this  hypothesis in the spirit of [fefferman] different classes of manifolds can be considered. Each of these choices corresponds, from the statistical point of view, to the choice of an hypothesis class for the hypothesis test. More formally, we say that the random vector $X$ satisfies the $\varepsilon$-manifold hypothesis in a hypothesis class $\mathcal{H}$ if there exists a manifold $Z \in \mathcal{H}$ such that $\mathbb{E}[\dist(X,Z)^2] <\varepsilon$. An illustration of the problem setting is given by \Cref{fig:manifold}.

</p>

# Differential Geometry
##  Morse Theory
<img align="left" width="200" src="assets/torus.png" />
<p style="text-align: justify;">
Given a smooth real manifold \(M\) and a smooth function \(f: M \rightarrow \mathbb{R}\), at any critical point \(x\) of \(f\), the notion of the <em>Hessian matrix</em> of \(f\) at \(x\) is well-defined. If, at every critical point, this matrix is invertible, then \(f\) is called a <em>Morse function</em>.

Since the Hessian is symmetric, at each critical point we can associate the number of negative eigenvalues of this matrix; this number is called the <em>index</em> of the critical point.

It turns out that the class of Morse functions on a manifold is strongly related to the topology of the manifold itself: for any \(f\), the \(k\)-th Betti number of \(M\) is bounded above by the number of critical points of \(f\) of index \(k\). These are the so-called (weak) <em>Morse inequalities</em>. Moreover, the function defines a way of decomposing \(M\), by gluing together different <em>handles</em>, giving rise to a so called <em>handle decomposition</em> of \(M\).

The applications are several: on one hand, finding "minimal" Morse functions on a manifold helps to describe its topology; on the other hand, critical points of functions (and more generally, of functionals) play a central role in optimization problems, dynamical systems (periodic solutions), functional analysis, theoretical physiscs and beyond. In particular for in optimization problems, counting these critical points provides a notion of the <em>complexity</em> of the associated problem.
</p>

## Stiefel Whitney Classes

## Lie Algebras and Groups

<p>
  When \(a \ne 0\), there are two solutions to \(ax^2 + bx + c = 0\) and they are
  \[x = {-b \pm \sqrt{b^2-4ac} \over 2a}.\]



$$x^2+\int_{0}^1f(x)dx$$
