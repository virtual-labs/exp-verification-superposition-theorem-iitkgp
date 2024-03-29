### Theory
<p>If a number of voltage or current source are acting simultaneously in a linear network, the resultant current in any branch is the algebraic sum of the currents that would be produced in it, when each source acts alone replacing all other independent sources by their internal resistances.
<br>
<h2>Circuit Diagram:</h2>
<div align="center">
<img src="images/pic1.JPG" />

***Fig.1 : Circuit for analysis of Superposition theorem***
</div>
<div align="center">
<img src="images/pic2.JPG" />

***Fig.2 : Circuit with only V<sub>2</sub> short circuited***
</div>
 
In given figure 1 apply superposition theorem , let us first take the sources V<sub>1</sub> alone at first replacing V<sub>2</sub> by short circuit as shown in figure 2.Here,

$$  I_{1'} = \frac{V_1}{\frac{R_2*R_3}{R_2+R_3}+R_1} $$

$$ I_{2'} = I_{1'}* \frac{R_3}{R_2+R_3} $$

$$ I_{3'} = I_{1'} - I_{2'} $$

<div align="center">
<img src="images/pic3.JPG" />

***Fig.3 : Circuit with only V<sub>1</sub> short circuited***
</div>
Next, removing V<sub>1</sub> by short circuit, let the circuit be energized by V<sub>2</sub> only as shown in figure 3. Then,

$$ I_{2''} = \frac{V_2}{\frac{R_2*R_3}{R_2+R_3}+R_2} $$

$$ I_{1''} = I_{2''}* \frac{R_3}{R_1+R_3} $$

$$ I_{3''} = I_{2''} - I_{1''} $$

As per superposition theorem,

$$ I_{3} = I_{3'} + I_{3''} $$

$$ I_{2} = I_{2'} - I_{2''} $$

$$ I_{1} = I_{1'} - I_{1''} $$

</p>         
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

