**Turing.jl** is a Julia library for general-purpose [probabilistic programming](https://en.wikipedia.org/wiki/Probabilistic_programming_language).
Turing allows the user to write models using the standard Julia syntax, 
and provides a wide range of Monte Carlo sampling and optimisation based 
inference methods for solving problems across probabilistic machine learning, 
Bayesian statistics and data science. Compared to other probabilistic programming languages, 
Turing specializes in modularity, and decouples the modelling language (i.e., the compiler) and inference methods. 
Turing's modular design and the high-level numerical language Julia make Turing remarkably extensible: new model families and inference methods can be easily added.

Current functionalities include:

- [General-purpose](https://turinglang.org/dev/tutorials/06-infinite-mixture-model/) probabilistic programming with an [intuitive modelling interface](https://turinglang.org/dev/tutorials/00-introduction/)
- Robust, efficient [Hamiltonian Monte Carlo (HMC)](https://github.com/TuringLang/AdvancedHMC.jl) sampling for differentiable posterior distributions
- [Particle MCMC](https://github.com/TuringLang/AdvancedPS.jl) sampling for complex posterior distributions involving discrete variables and stochastic control flows
- Compositional inference via Gibbs sampling that combines particle MCMC, HMC, [Random-Walk MH (RWMH)](https://github.com/TuringLang/AdvancedMH.jl) and [Elliptical Slice Sampling](https://github.com/TuringLang/Turing.jl/blob/master/src/inference/ess.jl)
- Advanced variational inference based on [ADVI](https://github.com/TuringLang/AdvancedVI.jl) and [Normalising Flows](https://github.com/TuringLang/Bijectors.jl)

- ## Want to contribute?

Turing was originally created and is now managed by Hong Ge. Current and past Turing team members include [Hong Ge](http://mlg.eng.cam.ac.uk/hong/), [Kai Xu](http://mlg.eng.cam.ac.uk/?portfolio=kai-xu), [Martin Trapp](http://martint.blog), [Mohamed Tarek](https://github.com/mohamed82008), [Cameron Pfiffer](https://business.uoregon.edu/faculty/cameron-pfiffer), [Tor Fjelde](http://retiredparkingguard.com/about.html).
You can see the complete list on Github: https://github.com/TuringLang/Turing.jl/graphs/contributors.

Turing is an open source project so if you feel you have some relevant skills and are interested in contributing, please get in touch. See the [Contributing](https://turinglang.org/dev/docs/contributing/guide) page for details on the process. You can contribute by opening issues on Github, implementing things yourself, and making a pull request. We would also appreciate example models written using Turing.

## Issues and Discussions
Issues related to bugs and feature requests are welcome on the [issues page](https://github.com/TuringLang/Turing.jl/issues), while discussions and questions about statistical applications and theory should place on the [Discussions page](https://github.com/TuringLang/Turing.jl/discussions) or [our channel](https://julialang.slack.com/messages/turing/) (`#turing`) in the Julia Slack chat. If you do not have an invitation to Julia's Slack, you can get one by going [here](https://julialang.org/slack/).


## Citing Turing.jl ##
If you use **Turing** for your research, please consider citing the following publication: Hong Ge, Kai Xu, and Zoubin Ghahramani: **Turing: a language for flexible probabilistic inference.** AISTATS 2018 [pdf](http://proceedings.mlr.press/v84/ge18b.html) [bibtex](https://github.com/TuringLang/Turing.jl/blob/master/CITATION.bib)
