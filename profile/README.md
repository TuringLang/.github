<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://turinglang.org/assets/logo/turing-logo-dark.svg">
    <img src="https://turinglang.org/assets/logo/turing-logo-light.svg" alt="Turing.jl logo" width="300">
  </picture>
</p>

**`Turing.jl`** is a Julia
[probabilistic programming](https://en.wikipedia.org/wiki/Probabilistic_programming_language)
package for Bayesian inference and likelihood-based estimation.

Current capabilities include:

- [Model specification](https://turinglang.org/docs/tutorials/00-introduction/)
  with the `@model` macro
- [Hamiltonian Monte Carlo](https://github.com/TuringLang/AdvancedHMC.jl)
  for differentiable target distributions
- [Particle MCMC](https://github.com/TuringLang/Turing.jl/blob/main/src/mcmc/particle_mcmc.jl)
  for posteriors involving discrete variables and stochastic control flow
- Gibbs sampling that combines particle MCMC, HMC,
  [random-walk Metropolis–Hastings](https://github.com/TuringLang/AdvancedMH.jl),
  [elliptical slice sampling](https://github.com/TuringLang/Turing.jl/blob/main/src/mcmc/ess.jl),
  and other transition kernels
- Variational inference with
  [ADVI](https://github.com/TuringLang/AdvancedVI.jl) and
  [normalising flows](https://github.com/TuringLang/Bijectors.jl)
- Maximum likelihood and maximum a posteriori
  [estimation](https://turinglang.org/docs/usage/mode-estimation/) through
  [Optimization.jl](https://docs.sciml.ai/Optimization/), using L-BFGS by default

## Project scope

Turing is maintained as grant-funded research software. Development prioritises
correctness, reproducibility, and stability within the documented scope.

Reports of incorrect results or unexpected failures should include a minimal
reproducible example where practical. Maintenance and review capacity is
necessarily limited.

## Open code and reproducible research

Turing.jl is distributed under the
[MIT License](https://github.com/TuringLang/Turing.jl/blob/main/LICENCE). Its
source code, tests, and documentation are public, allowing methods and
implementations to be inspected and reused. Reproducible analyses should archive
the analysis code and Julia project environment, and record data provenance,
random seeds, and relevant computational settings.

## Helping out

See the [guidance for helping out](../CONTRIBUTING.md) with small fixes, new
feature proposals, and reviewing. Questions about a scoped task may be raised
on its issue, in the
[Turing channel on Julia Slack](https://julialang.slack.com/archives/CCYDC34A0),
or on [Julia Discourse](https://discourse.julialang.org/tag/turing).

## Citing Turing.jl

If you use Turing.jl in published work, please cite:

[**Turing.jl: A General-Purpose Probabilistic Programming Language**](https://doi.org/10.1145/3711897)<br>
Tor Erlend Fjelde, Kai Xu, David Widmann, Mohamed Tarek, Cameron Pfiffer, Martin Trapp, Seth D. Axen, Xianda Sun, Markus Hauru, Penelope Yong, Will Tebbutt, Zoubin Ghahramani, Hong Ge<br>
ACM Transactions on Probabilistic Machine Learning, 1(3):1–48, 2025.

[**Turing: A Language for Flexible Probabilistic Inference**](https://proceedings.mlr.press/v84/ge18b.html)<br>
Hong Ge, Kai Xu, Zoubin Ghahramani<br>
Proceedings of the Twenty-First International Conference on Artificial Intelligence and Statistics, PMLR 84:1682–1690, 2018.

<details>

<summary>Expand for BibTeX</summary>

```bibtex
@article{10.1145/3711897,
  author = {Fjelde, Tor Erlend and Xu, Kai and Widmann, David and Tarek, Mohamed and Pfiffer, Cameron and Trapp, Martin and Axen, Seth D. and Sun, Xianda and Hauru, Markus and Yong, Penelope and Tebbutt, Will and Ghahramani, Zoubin and Ge, Hong},
  title = {{Turing.jl}: A General-Purpose Probabilistic Programming Language},
  journal = {ACM Trans. Probab. Mach. Learn.},
  year = {2025},
  volume = {1},
  number = {3},
  pages = {1--48},
  month = aug,
  publisher = {Association for Computing Machinery},
  address = {New York, NY, USA},
  doi = {10.1145/3711897},
  url = {https://doi.org/10.1145/3711897},
}

@inproceedings{pmlr-v84-ge18b,
  author = {Ge, Hong and Xu, Kai and Ghahramani, Zoubin},
  title = {{Turing}: A Language for Flexible Probabilistic Inference},
  booktitle = {Proceedings of the Twenty-First International Conference on Artificial Intelligence and Statistics},
  editor = {Storkey, Amos and Perez-Cruz, Fernando},
  series = {Proceedings of Machine Learning Research},
  volume = {84},
  pages = {1682--1690},
  year = {2018},
  month = {09--11 Apr},
  publisher = {PMLR},
  pdf = {https://proceedings.mlr.press/v84/ge18b/ge18b.pdf},
  url = {https://proceedings.mlr.press/v84/ge18b.html},
}
```

</details>
