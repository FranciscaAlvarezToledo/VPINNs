# VPINNs

## Problema
Resolver la ecuación diferencial

$-\Delta u &= f(x), \hspace{1cm} x \in \Omega =(1,0) \\
u|_{\partial \Omega} &= 0.$

La Formulación variacional viene dada por
$\int_{\Omega} \nabla u \nabla v \, dx - \int_{\partial \Omega} u\, v \, ds= \int_{\Omega} f\, v \, dx,$
para todo $v \in H_{0}^{1}(\Omega)$. La integral sobre el borde en la expresión anterior puede ser omitida.
