Compte rendu TP2 Analyse numérique : Interpolation Numérique
Partie Théorique

Principe de l'interpolation polynomiale:

En mathématiques, en analyse numérique, l'interpolation polynomiale est une technique d'interpolation d'un ensemble de données ou d'une fonction par un polynôme. En d'autres termes, étant donné un ensemble de points (obtenu, par exemple, à la suite d'une expérience), on cherche un polynôme qui passe par tous ces points, et éventuellement vérifie d'autres conditions, de degré si possible le plus bas.

Principe de l'interpolation de Lagrange:

Le polynôme d’interpolation de Lagrange P(x) est le polynôme unique d’ordre n, qui passe exactement par ces (n+1) points,il permettent d'interpoler une série de points par un polynôme

 

avec
 

Principe de phénomène de Runge:
{
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    " #### <p style=\"color:#cd8235\" >Principe de l'interpolation de Lagrange:</p>\n",
    " Le polynôme d’interpolation de Lagrange P(x) est le polynôme unique d’ordre n, qui\n",
    " passe exactement par ces (n+1) points,il permettent d'interpoler une série de points par un polynôme\n",
    " \n",
    " $$ \\circ \\hspace{0.5cm}  P(x)=\\sum_{i=0} f(xi)Li(x) $$\n",
    " >avec\n",
    " $$ \\circ \\hspace{0.5cm}  Li(x)=\\prod _{k=0 k\\neq {i}}  (x-xk)/(xi-xk) $$"
   ]
  },
