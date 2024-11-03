# Bayesian Statistics
This repository contain Bayesians statistics implementation in R and Python. The directories available are:

### Non-parametric Bayesian inference
* DPMM: contains the R code to implement Dirichlet Process Mixture Model (DPMM) using `NIMBLE` on the `iris` dataset. The primary referece to understand the theory behind DPMMs are the [Bayesian non-parametric tutorials](https://tamarabroderick.com/tutorial_2017_simons.html) by Tamara Broderick.
* nature_of_priors: Examined the nature of a popular non-parametric bayesian prior called Dirichlet process. Primary reference for this file is the [DP density estimation tutorial](https://www.pymc.io/projects/examples/en/latest/mixture_models/dp_mix.html) by PyMC.
### Statistical software for Bayesian Statistics
* Nimble: Understanding `NIMBLE` syntax using a simple bayesian capture-recapture model example taken from the [`NIMBLE` tutorial](https://oliviergimenez.github.io/banana-book/intronimble.html) by Olivier Gimenez.
* STAN: Learning to perform posterior inference using `RStan` while following Chapters 6,7, and 8 of [Bayes Rules!](https://www.bayesrulesbook.com/) by Alicia A. Johnson, Miles Q. Ott, and Mine Dogucu.

### Miscellaneous
* hare_lynx_dynamics: Performed likelihood estimation in R to estimate the parameters associated with the Lotka–Volterra system of differential equations.
* some_plots: Examined the nature of two popular priors used in Bayesian Statistics - beta and Dirichlet priors. Analyzed the effect of parameter choices on the nature of the resulting distributions.
