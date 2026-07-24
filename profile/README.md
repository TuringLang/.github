<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://turinglang.org/assets/logo/turing-logo-dark.svg">
    <img src="https://turinglang.org/assets/logo/turing-logo-light.svg" alt="Turing.jl logo" width="300">
  </picture>
</p>

**`Turing.jl`** is a general-purpose [probabilistic programming](https://en.wikipedia.org/wiki/Probabilistic_programming_language) language implemented in Julia, allowing models to be specified through an intuitive `@model` syntax. It provides a broad range of Monte Carlo sampling and optimisation-based inference methods.

Current capabilities include:

- [Intuitive model specification](https://turinglang.org/docs/tutorials/00-introduction/) via the `@model` macro
- [Hamiltonian Monte Carlo](https://github.com/TuringLang/AdvancedHMC.jl) for differentiable target distributions
- [Particle MCMC](https://github.com/TuringLang/AdvancedPS.jl) for posteriors involving discrete variables and stochastic control flow
- Gibbs sampling, combining particle MCMC, HMC, [Random-Walk Metropolis–Hastings](https://github.com/TuringLang/AdvancedMH.jl), [elliptical slice sampling](https://github.com/TuringLang/Turing.jl/blob/main/src/mcmc/ess.jl), and others
- Variational inference via [ADVI](https://github.com/TuringLang/AdvancedVI.jl) and [normalising flows](https://github.com/TuringLang/Bijectors.jl)
- Maximum-likelihood and maximum a posteriori [estimation](https://turinglang.org/docs/usage/mode-estimation/) via [L-BFGS optimisation](https://docs.sciml.ai/Optimization/)

> [!IMPORTANT]
> Turing.jl is maintained primarily by academic researchers at grant-funded research institutions, with correspondingly limited capacity for triage and review.
>
> If you would like to contribute, we ask that proposals for new features be submitted first, so that the TuringLang team can indicate whether they are aligned with the project's direction before implementation begins. Bug fixes and small changes are very welcome as direct pull requests. Reviewer privileges are reserved for those with a sustained record of substantive contributions, or for individuals explicitly invited by a team member. Accounts used for spam or abuse will be blocked and reported; moderation is otherwise undertaken at our discretion, as capacity permits.

## Citing Turing.jl

If you have used Turing.jl in your work, we would be very grateful if you could cite the following:

[**Turing.jl: a general-purpose probabilistic programming language**](https://doi.org/10.1145/3711897)  
Tor Erlend Fjelde, Kai Xu, David Widmann, Mohamed Tarek, Cameron Pfiffer, Martin Trapp, Seth D. Axen, Xianda Sun, Markus Hauru, Penelope Yong, Will Tebbutt, Zoubin Ghahramani, Hong Ge  
ACM Transactions on Probabilistic Machine Learning, 2025

[**Turing: A Language for Flexible Probabilistic Inference**](https://proceedings.mlr.press/v84/ge18b.html)  
Hong Ge, Kai Xu, Zoubin Ghahramani  
Proceedings of the Twenty-First International Conference on Artificial Intelligence and Statistics, PMLR 84:1682-1690, 2018.

<details>

<summary>Expand for BibTeX</summary>

```bibtex
@article{10.1145/3711897,
author = {Fjelde, Tor Erlend and Xu, Kai and Widmann, David and Tarek, Mohamed and Pfiffer, Cameron and Trapp, Martin and Axen, Seth D. and Sun, Xianda and Hauru, Markus and Yong, Penelope and Tebbutt, Will and Ghahramani, Zoubin and Ge, Hong},
title = {Turing.jl: a general-purpose probabilistic programming language},
year = {2025},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3711897},
doi = {10.1145/3711897},
note = {Just Accepted},
journal = {ACM Trans. Probab. Mach. Learn.},
month = feb,
}

@InProceedings{pmlr-v84-ge18b,
  title = 	 {Turing: A Language for Flexible Probabilistic Inference},
  author = 	 {Ge, Hong and Xu, Kai and Ghahramani, Zoubin},
  booktitle = 	 {Proceedings of the Twenty-First International Conference on Artificial Intelligence and Statistics},
  pages = 	 {1682--1690},
  year = 	 {2018},
  editor = 	 {Storkey, Amos and Perez-Cruz, Fernando},
  volume = 	 {84},
  series = 	 {Proceedings of Machine Learning Research},
  month = 	 {09--11 Apr},
  publisher =    {PMLR},
  pdf = 	 {http://proceedings.mlr.press/v84/ge18b/ge18b.pdf},
  url = 	 {https://proceedings.mlr.press/v84/ge18b.html},
}
```

</details>
