# Bayesian Statistics
This repository contain Bayesian statistics implementation in R and Python. The directories available are:

### Non-parametric Bayesian inference
* DPMM: contains the R code to implement Dirichlet Process Mixture Model (DPMM) using `NIMBLE` on the `iris` dataset. The primary reference to understand the theory behind DPMMs are the [Bayesian non-parametric tutorials](https://tamarabroderick.com/tutorial_2017_simons.html) by Tamara Broderick.
* nature_of_priors: Examined the nature of a popular non-parametric bayesian prior called Dirichlet process. Primary reference for this file is the [DP density estimation tutorial](https://www.pymc.io/projects/examples/en/latest/mixture_models/dp_mix.html) by [PyMC](https://www.pymc.io/welcome.html).

### Statistical software for Bayesian Statistics
* Nimble: Understanding [`NIMBLE`](https://r-nimble.org/) syntax using a simple bayesian capture-recapture model example taken from the [`NIMBLE` tutorial](https://oliviergimenez.github.io/banana-book/intronimble.html) by Olivier Gimenez.
* STAN: Learning to perform posterior inference using [`RStan`](https://mc-stan.org/users/interfaces/rstan) while following Chapters 6,7, and 8 of [Bayes Rules!](https://www.bayesrulesbook.com/) by Alicia A. Johnson, Miles Q. Ott, and Mine Dogucu.
* PyMC: Learning to perform bayesian posterior inference using PyMC module. The primary reference for this folder are: 
    - PyMC's [example gallery](https://www.pymc.io/projects/examples/en/latest/gallery.html#)
    - Martin Osvaldo A, Kumar Ravin; Lao Junpeng, [_Bayesian Modeling and Computation in Python_](https://bayesiancomputationbook.com/welcome.html) Boca Ratón, 2021. ISBN 978-0-367-89436-8
    - Paper introducing PyMC3: Salvatier J, Wiecki TV, Fonnesbeck C. 2016. _Probabilistic programming in Python using PyMC3_. PeerJ Computer Science 2:e55 https://doi.org/10.7717/peerj-cs.55

### Miscellaneous
* hare_lynx_dynamics: Performed likelihood estimation in R to estimate the parameters associated with the Lotka–Volterra system of differential equations.
* some_plots: Examined the nature of two popular priors used in Bayesian Statistics - beta and Dirichlet priors. Analyzed the effect of parameter choices on the nature of the resulting distributions.

# Some useful resources
1. [PyMC Github page:](https://github.com/pymc-devs/pymc): https://github.com/pymc-devs/pymc
2. [Course resource on PyMC3](https://people.duke.edu/~ccc14/sta-663-2017/19A_PyMC3.html): https://people.duke.edu/~ccc14/sta-663-2017/19A_PyMC3.html
3. [Course resource on PyStan](https://people.duke.edu/~ccc14/sta-663-2017/19B_Pystan.html)
