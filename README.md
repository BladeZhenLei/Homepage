<p align="center">
$Welcome$ $to$ $Blade(Zhen)'s$ $Homepage!$
</p> 
<p align="center"><img src= "https://user-images.githubusercontent.com/66701331/182988392-6dc55f54-b27b-414b-a433-48f172b1209d.png" width="100" height="100" ></p>

I love Number Theory, Graph Theory, and combinatorics.
<br/>
Here I want to share some fun stuffs about math. 
<p/>

(...still being developed...)

See 
<br/>
<a href="https://github.com/BladeZhenLei/Riemann-Hypothesis/blob/main/README.md"> Introduction to Riemann Hypothesis </a>
<br/>
for The Biggest Mystery in Mathematics. 

See
<br/>
...
<br/>
for some conjectures I made.

Also see
<br/>
<a href="https://bladezhenlei.github.io/Gallery-Parametric/"> Parametric </a>
<br/>
<a href="https://bladezhenlei.github.io/Gallery-Polar/"> Polar </a>
<br/>
<a href="https://bladezhenlei.github.io/Gallery-Fractal/"> Fractal </a>
<br/>
for archieves of mathematical art.

<p align="center">
$Thank$ $you!$
</p>


<html lang="en">
<head>
<meta http-equiv="content-type" content="text/html; charset=utf-8">
<title>Don't delete!</title>
<script type="text/javascript" charset="utf-8" src="
https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML,
https://vincenttam.github.io/javascripts/MathJaxLocal.js"></script>
</head>
<body>

<p>This page is for testing MathJax in my blog.  I wrote some custom
shorthand like $\zeros \in \R^n$.</p>

<h2>Problem</h2>

<p>For sequences of numbers, <em>limit inferior</em> and <em>limit
superior</em> are defined as $\liminf (a_n):=\sup\{\inf\{a_k:k \ge
n\}\}$ and $\limsup (a_n):=\inf\{\sup\{a_k:k \ge n\}\}$ respectively;
for sequences of sets, they are defined as $\displaystyle
\bigcup_{n=1}^{\infty} \bigcap_{k=n}^{\infty} A_k$ and $\displaystyle
\bigcap_{n=1}^{\infty} \bigcup_{k=n}^{\infty} A_k$ respectively.</p>

<p><strong>Why are they consistent?</strong></p>

<h2>Discussion</h2>

<p>It suffices to find a relation between '&lt;' and '&sube;': $\{x
\le a\} \subseteq \{x \le b\} \iff a \le b$.</p>

<p>Claim: $\displaystyle \bigcup_{a \in A} \{x \le a\} = \{x \le \sup
A\}$.</p>

<p><em>Proof</em>:</p>

<div class="myeqn">
\[
  \begin{aligned}
    & x \in \bigcup_{a \in A} \{x \le a\} \\
    \iff& x \le a \;\forall a \in A \\
    \iff& x \text{ is a lower bound of } A \\
    \iff& x \le \inf A
  \end{aligned}
\]
</div>

<p>The last step is due to the defintion of infimum (<em>greatest</em>
lower bound).</p>

<p>With the above claim, one has</p>

<div class="myeqn">
\[
  \begin{aligned}
    & \bigcap_{n=1}^{\infty} \bigcup_{k=n}^{\infty} \{x \le a_k\} \\
    =& \bigcap_{n=1}^{\infty} \bigcup_{a \in \{a_k:k \ge n\}} \{x \le a\} \\
    =& \bigcap_{n=1}^{\infty} \{ x \le \sup \{a_k:k \ge n\}\} \\
    =& \{x \le \inf\sup \{a_k:k \ge n\}\}
  \end{aligned}
\]
</div>

<p>Hence, one can see that $\sup\inf \{a_k:k \ge n\} \le \inf\sup
\{a_k:k \ge n\}$ and $\displaystyle \bigcup_{n=1}^{\infty}
\bigcap_{k=n}^{\infty} \{x \le a_k\} \subseteq \bigcap_{n=1}^{\infty}
\bigcup_{k=n}^{\infty} \{x \le a_k\}$ share something in common.</p>

<p>
<a href="//validator.w3.org/check?uri=referer"><img
  src="/images/valid-html401.png" alt="Valid HTML 4.01 Strict"
  height="31" width="88"></a>
<a href="//jigsaw.w3.org/css-validator/check/referer"><img
  src="/images/valid-css.png" alt="Valid CSS" height="31" width="88">
</a></p>
</body>
</html>
