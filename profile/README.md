**Turing.jl** is a Julia library for general-purpose [probabilistic programming](https://en.wikipedia.org/wiki/Probabilistic_programming_language).
Turing allows the user to write models using the standard Julia syntax, 
and provides a wide range of Monte-Carlo sampling and optimisation-based 
inference methods for solving problems across probabilistic machine learning, 
Bayesian statistics and data science. Compared to other probabilistic programming languages, 
Turing specialises in modularity and decouples the modelling language (i.e., the compiler) and inference methods. 
Turing's modular design and the high-level numerical language Julia make Turing remarkably extensible, allowing for the easy addition of new model families and inference methods.

Current functionalities include:

- [General-purpose](https://turinglang.org/docs/tutorials/06-infinite-mixture-model/) probabilistic programming with an [intuitive modelling interface](https://turinglang.org/docs/tutorials/00-introduction/)
- Robust, efficient [Hamiltonian Monte Carlo (HMC)](https://github.com/TuringLang/AdvancedHMC.jl) sampling for differentiable posterior distributions
- [Particle MCMC](https://github.com/TuringLang/AdvancedPS.jl) sampling for complex posterior distributions involving discrete variables and stochastic control flows
- Compositional inference via Gibbs sampling that combines particle MCMC, HMC, [Random-Walk MH (RWMH)](https://github.com/TuringLang/AdvancedMH.jl) and [Elliptical Slice Sampling](https://github.com/TuringLang/Turing.jl/blob/main/src/mcmc/ess.jl)
- Advanced variational inference based on [ADVI](https://github.com/TuringLang/AdvancedVI.jl) and [Normalising Flows](https://github.com/TuringLang/Bijectors.jl)

## Citing Turing.jl

If you have used Turing.jl in your work, we would be very grateful if you could cite the following:

[**Turing.jl: a general-purpose probabilistic programming language**](https://doi.org/10.1145/3711897)  
Tor Erlend Fjelde, Kai Xu, David Widmann, Mohamed Tarek, Cameron Pfiffer, Martin Trapp, Seth D. Axen, Xianda Sun, Markus Hauru, Penelope Yong, Will Tebbutt, Zoubin Ghahramani, Hong Ge  
ACM Transactions on Probabilistic Machine Learning, 2025 (_Just Accepted_)  

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
