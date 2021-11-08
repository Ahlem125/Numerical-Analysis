# Numerical-Analysis
## Introduction chapitre 1
 les solutions de l’´equation f(x) = 0  et f(α)=0, α est un zéro de f Le calcul de telle α n'est pas facile en générale analytiqument.C'est pourquoiqs, on a recours à des méthodes iteratives Pour approcher telle α.  L’id´ee g´en´erale est de contruire une suite (xn) qui converge vers

#### On se dispose de 3 m´ethodes pour contruire telle (xn), qui sont  :
* la méthode de la dichotomie (ou bissection)
* la méthode de point ﬁxe
* la méthode de Newton

## Partie Théorique
1.  Principe de la méthode de dichotomie ( ou bisection ) :
Considérons une fonction f continue sur un intervalle [a,b]. On suppose que f admet une et une seule racine α dans ]a, b[ et que f(a)*f(b)<0.
On note x=(a+b)/2le milieu de l'intervale [a,b]

* Si f(x) = 0, c’est la racine de f et le problème est résolu(α=x)
* Si $f(x) \neq 0$, nous regardons le signe de f(a)* f(x).
      si f(a)*f(x)<0 donc la racine se trouve dans l'intervalle [a,x]
      si f(a)*f(x)>0 donc la racine se trouve dans l'intervalle [x,b]
      
      
On recommence le processus en segmente chaque fois sur 2 l'intervalle ou quelle la racine est appartient jusqu'a avoir une valeur approcher sur l'intervalle adéquat.

2.  Principe de la méthode de point fixe

Le principe de cette méthode consiste à transformer l’équation f(x) = 0 en une équation équivalente g(x) = x . Le point α est alors un point fixe de g. Approcher les zéros de f revient à approcher les points fixes de g. Le choix de la fonction g est motivé par les exigences du théorème de point fixe. En effet, elle doit être contractante dans un voisinage I de α, ce qui revient à vérifier que : $|g_0(x)| &lt; 1$ sur ce voisinage
