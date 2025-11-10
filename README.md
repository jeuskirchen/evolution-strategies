# evolution-strategies
Experimenting with search gradients and evolution strategies.

<p align="center">
    <img src="figures/0.png" alt="" width=900/>
</p>

1D example of an optimization process using natural evolution strategies. The solution is $x=9$ (value with maximum fitness) and the initialization is at $x=0$. Over 20 generations, the parameters of the search distribution are updated such that its mean is approximately at the solution value. The fitness function is assumed to be a black box. Even if the fitness function itself is non-differentiable, the fitness values of the samples imply a fitness gradient with respect to the search distribution's parameters. 

<p align="center">
    <img src="figures/nes.gif?v=1" alt="" style="width: 970px; height: auto;"/>
</p>