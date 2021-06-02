## Caputo-fractional-derivative

Function `caputo.m` computes the Caputo fractional derivative of order <img src="https://render.githubusercontent.com/render/math?math=0<\alpha<1"> of a given function <img src="https://render.githubusercontent.com/render/math?math=f\in C^4[0,T]">, by using the (<img src="https://render.githubusercontent.com/render/math?math=4 - \alpha">)-th order quadrature formule developed by Cao and Li in [1].

Function `quadrature.m` returns the weighted coefficients of the (<img src="https://render.githubusercontent.com/render/math?math=4 - \alpha">)-th order quadrature formule (2.7) developed in [1], and function `caputo.m` uses these weights to evaluate numerically the Caputo derivative of order alpha.

Scripts `test1.m` and `test2.m` evaluate numerically the Caputo fractional derivative of order <img src="https://render.githubusercontent.com/render/math?math=\alpha">  of <img src="https://render.githubusercontent.com/render/math?math=f(t)=t^4"> and <img src="https://render.githubusercontent.com/render/math?math=f(t)=e^{2t}"> respectively, for <img src="https://render.githubusercontent.com/render/math?math=t\in [0,T]">. Approximation errors and convergence orders are illustrated at <img src="https://render.githubusercontent.com/render/math?math=T=1">. See examples 3.1 and 3.2 at [1].

## References

[1] [Cao, J., Li, C., & Chen, Y. (2015). High-order approximation to Caputo derivatives and Caputo-type advection-diffusion equations (II). Fractional calculus and  Applied analysis, 18(3), 735-761](https://www.degruyter.com/document/doi/10.1515/fca-2015-0045/html).
