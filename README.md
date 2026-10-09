# Ivan Bioli

**Computational scientist: numerical methods and machine learning for problems governed by physics.**

[![Website](https://img.shields.io/badge/Website-ivanbioli.github.io-1D3F8F?style=flat-square)](https://ivanbioli.github.io)
[![Google Scholar](https://img.shields.io/badge/Google_Scholar-1D3F8F?style=flat-square&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=yYMTqgYAAAAJ)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0003--1172--4362-1D3F8F?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0009-0003-1172-4362)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-1D3F8F?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ivan-bioli-059a001a6/)
[![Email](https://img.shields.io/badge/Email-ivan.bioli%40gmail.com-1D3F8F?style=flat-square&logo=gmail&logoColor=white)](mailto:ivan.bioli@gmail.com)

I build efficient, mathematically grounded solvers, from the model to tested code that runs fast.
I'm a Marie Skłodowska-Curie Doctoral Fellow at the University of Pavia (IN-DEEP European Doctoral Network), working on deep learning for PDEs with applications to inverse problems in computational oncology. Before that: MSc in Computational Science and Engineering at EPFL, BSc in Mathematics at the University of Pisa, and reinforcement learning for live race strategy at the Alfa Romeo F1 Team.

**Open to collaborations in research and industry:** simulation, surrogate modelling, optimisation and machine learning for engineering and scientific problems.

---

### What I work on

- **Scientific machine learning:** neural PDE solvers, physics-informed training, optimisers for neural networks
- **Numerical PDEs:** finite elements and isogeometric analysis, discretisation and error analysis
- **Inverse problems and UQ:** Bayesian inversion and model calibration with neural surrogates
- **Numerical linear algebra:** low-rank methods, Riemannian optimisation, randomised preconditioning

### Selected code

| Project | What it is | |
|---|---|---|
| [**ssbroyden_optimistix**](https://github.com/IvanBioli/ssbroyden_optimistix) | Self-Scaled Broyden quasi-Newton methods (SSBFGS, SSDFP, …) with a strong-Wolfe Zoom line search, as an add-on to [Optimistix](https://github.com/patrick-kidger/optimistix) | JAX · [arXiv:2603.10599](https://doi.org/10.48550/arXiv.2603.10599) |
| [**preconditioned-natural-gradient**](https://github.com/IvanBioli/preconditioned-natural-gradient) | Natural gradient descent for PINNs accelerated with randomised numerical linear algebra | *CMAME* (to appear) · [arXiv:2505.11638](https://arxiv.org/abs/2505.11638) |
| [**TT_for_GPE**](https://github.com/IvanBioli/TT_for_GPE) | Riemannian optimisation on low-rank tensor-train manifolds for Gross–Pitaevskii ground states | [arXiv:2609.37103](https://arxiv.org/abs/2609.37103) |
| [**ldnets-tumor-inversion**](https://github.com/IvanBioli/ldnets-tumor-inversion) | Latent-dynamics surrogates for uncertainty-aware Bayesian inversion of tumor growth models | in preparation |
| [**riemannian-spdmatrixeq**](https://github.com/IvanBioli/riemannian-spdmatrixeq) | Preconditioned low-rank Riemannian optimisation for SPD linear matrix equations | MATLAB · [*SISC* 47(2), 2025](https://doi.org/10.1137/24M1680429) |

### Open-source contributions

- [JuliaNLSolvers/Optim.jl](https://github.com/JuliaNLSolvers/Optim.jl): fix to preconditioner updates in nonlinear conjugate gradient (merged)
- [NicolasBoumal/manopt](https://github.com/NicolasBoumal/manopt): new β-update rules for Riemannian conjugate gradient, after Sato (merged)

### Teaching

- [**elementifiniti2526**](https://github.com/IvanBioli/elementifiniti2526): exercise material in Julia for the *Finite Elements* course at the University of Pavia (in Italian)
- Lecturer of *Introduction to Julia Programming for Data Science and Scientific Computing*, University of Pavia

### Toolbox

**Python** (JAX, PyTorch) · **Julia** (Lux.jl, CUDA.jl, Krylov.jl) · **MATLAB** · **C/C++** · LaTeX

---

<sub>Publications, talks and CV: <a href="https://ivanbioli.github.io">ivanbioli.github.io</a></sub>
