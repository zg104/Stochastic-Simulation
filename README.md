# Stochastic-Simulation

## Here are several perceptions and concepts of stochastic simulation.

When we are told to solve a high dimensional data with a lot of features. 
We try to calculate something analytically with the full parameterization of 2^n.

So, how can we lower the parameters?

- x = (x1,x2,...,xn) --> multi-normal
- Markov Chain
- Mixture models
- graphical models (undirected, DAGS)
- hardcore models
- Gaussian process
- Hiden Markov Models (HMM)

Given the model, how can we deal with the problem from the perspective of probability?

Computing probabilities of random vectors which involves high dimensional intergrals.

- 1 directly estimate
+ MH algorithm
+ Gibbs sampling

- 2 exploit the structure 
+ Markov Chains --> P(x(t) = j | x(0) = i) = (M^t)_i,j
+ Forward / Backword equations
+ spectual decomposition / cholesky decomposition
+ pseudo-likelihood / steepest descent / Newton Method (Bayesian)
+ EM algorithm
