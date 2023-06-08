# Nominal Sets and Exchangeable Statistical Processes

Supervised by Prof. Sam Staton.

## Clustering Example

![](generator.png)
![](instance.png)
![](dataset.svg)
![](map.svg)

Example couresy of [LazyPPL](https://lazyppl.bitbucket.io) [source](https://lazyppl.bitbucket.io/ClusteringDemo.html)

## Nominal Sets.

### Support
#### Definition

A set $A \subseteq \mathbb{A}$ is a support for $x \in X$ if $\forall \pi \in \text{Perm } \mathbb{A}, ((\forall a \in A) \pi a = a) \Rightarrow \pi x = x$.

### The Category Nom
#### Definition

A nominal set is a $\text{Perm } \mathbb{A}$-set such that all of the elements are finitely supported.

#### Definition

These with equivariant actions for the category $\textbf{Nom}$.

## Goal

> Since MCMC sampling algorithms for Dirichlet process mixtures became available in the 1990s and made latent variable models with nonparametric Bayesian components applicable to practical problems, the development of Bayesian nonparametrics has experienced explosive growth [9, 10]. Arguably, though, the results available so far have only scratched the surface. *The repertoire of available models is still mostly limited to using the Gaussian process, the Dirichlet process, the beta process, and generalizations derived from those.* In principle, Bayesian nonparametric models may be defined on any infinite-dimensional mathematical object of possible interest to machine learning and statistics. Possible examples are kernels, infinite graphs, special classes of functions (e.g. piecewise continuous or Sobolev functions), and permutations.
"Bayesian Nonparametric Models" by Orbanz and Teh 2017 [source](https://link.springer.com/referenceworkentry/10.1007/978-1-4899-7687-1_928)
