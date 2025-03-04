**Turing.jl** is a Julia library for general-purpose [probabilistic programming](https://en.wikipedia.org/wiki/Probabilistic_programming_language).
Turing allows the user to write models using the standard Julia syntax, 
and provides a wide range of Monte Carlo sampling and optimisation based 
inference methods for solving problems across probabilistic machine learning, 
Bayesian statistics and data science. Compared to other probabilistic programming languages, 
Turing specializes in modularity, and decouples the modelling language (i.e., the compiler) and inference methods. 
Turing's modular design and the high-level numerical language Julia make Turing remarkably extensible: new model families and inference methods can be easily added.

Current functionalities include:

- [General-purpose](https://turinglang.org/docs/tutorials/06-infinite-mixture-model/) probabilistic programming with an [intuitive modelling interface](https://turinglang.org/docs/tutorials/00-introduction/)
- Robust, efficient [Hamiltonian Monte Carlo (HMC)](https://github.com/TuringLang/AdvancedHMC.jl) sampling for differentiable posterior distributions
- [Particle MCMC](https://github.com/TuringLang/AdvancedPS.jl) sampling for complex posterior distributions involving discrete variables and stochastic control flows
- Compositional inference via Gibbs sampling that combines particle MCMC, HMC, [Random-Walk MH (RWMH)](https://github.com/TuringLang/AdvancedMH.jl) and [Elliptical Slice Sampling](https://github.com/TuringLang/Turing.jl/blob/main/src/mcmc/ess.jl)
- Advanced variational inference based on [ADVI](https://github.com/TuringLang/AdvancedVI.jl) and [Normalising Flows](https://github.com/TuringLang/Bijectors.jl)

## Citing Turing.jl ##
If you use **Turing** for your research, please consider citing the following publication: Hong Ge, Kai Xu, and Zoubin Ghahramani: **Turing: a language for flexible probabilistic inference.** AISTATS 2018 [pdf](http://proceedings.mlr.press/v84/ge18b.html) [bibtex](https://github.com/TuringLang/Turing.jl/blob/main/CITATION.bib)
