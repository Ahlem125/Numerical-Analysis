# Numerical-Analysis
## Introduction chapitre 1
 >les solutions de l’´equation f(x) = 0  et f(α)=0, α est un zéro de f Le calcul de telle α n'est pas facile en générale analytiqument.C'est pourquoiqs, on a recours à des méthodes iteratives Pour approcher telle α.  L’id´ee g´en´erale est de contruire une suite (xn) qui converge vers

#### On se dispose de 3 m´ethodes pour contruire telle (xn), qui sont  :
* la méthode de la dichotomie (ou bissection)
* la méthode de point ﬁxe
* la méthode de Newton

## Partie Théorique
1.  Principe de la méthode de dichotomie ( ou bisection ) :
Considérons une fonction f continue sur un intervalle [a,b]. On suppose que f admet une et une seule racine α dans ]a, b[ et que f(a)*f(b)<0.
On note x=(a+b)/2le milieu de l'intervale [a,b]

* Si f(x) = 0, c’est la racine de f et le problème est résolu(α=x)
* Si $ f(x) \neq 0$, nous regardons le signe de $f(a)* f(c)$.

$$ \circ \hspace{0.5cm} Si \hspace{0.5cm} f(a)*f(c) &lt; 0 \Longrightarrow    α\in ]a, c[$$$$ \circ \hspace{0.5cm} Si \hspace{0.5cm} f(c)* f(b) &lt; 0 \Longrightarrow   α\in]c, b[$$

On recommence le processus en prenant l’intervalle [a, c] au lieu de [a, b] dans le premier cas, et l’intervalle [c, b] au lieu de [a, b] dans le second cas. De cette manière, on construit par récurrence sur n trois suites $(a_n)$, $(b_n)$ et $(c_n)$ telles que $a_0 = a$, $b_0 = b$ et telles que pour tout n ≥ 0,
