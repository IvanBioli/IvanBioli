# Hi, I'm Ivan 👋

**Computational scientist: numerical methods and machine learning for problems governed by physics.**

<a href="https://ivanbioli.github.io"><img alt="Website" src="https://img.shields.io/badge/-ivanbioli.github.io-0B1A33?style=flat&logo=googlechrome&logoColor=white"/></a> &nbsp;
<a href="https://scholar.google.com/citations?user=yYMTqgYAAAAJ"><img alt="Google Scholar" src="https://img.shields.io/badge/-Google_Scholar-0B1A33?style=flat&logo=googlescholar&logoColor=4285F4"/></a> &nbsp;
<a href="https://orcid.org/0009-0003-1172-4362"><img alt="ORCID" src="https://img.shields.io/badge/-ORCID-0B1A33?style=flat&logo=orcid&logoColor=A6CE39"/></a> &nbsp;
<a href="https://www.linkedin.com/in/ivan-bioli-059a001a6/"><img alt="LinkedIn" src="https://img.shields.io/badge/-LinkedIn-0B1A33?style=flat&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iIzBBNjZDMiIgZD0iTTIwLjQ0NyAyMC40NTJoLTMuNTU0di01LjU2OWMwLTEuMzI4LS4wMjctMy4wMzctMS44NTItMy4wMzctMS44NTMgMC0yLjEzNiAxLjQ0NS0yLjEzNiAyLjkzOXY1LjY2N0g5LjM1MVY5aDMuNDE0djEuNTYxaC4wNDZjLjQ3Ny0uOSAxLjYzNy0xLjg1IDMuMzctMS44NSAzLjYwMSAwIDQuMjY3IDIuMzcgNC4yNjcgNS40NTV2Ni4yODZ6TTUuMzM3IDcuNDMzYTIuMDYyIDIuMDYyIDAgMSAxIDAtNC4xMjQgMi4wNjIgMi4wNjIgMCAwIDEgMCA0LjEyNHpNNy4xMTkgMjAuNDUySDMuNTU1VjloMy41NjR2MTEuNDUyek0yMi4yMjUgMEgxLjc3MUMuNzkyIDAgMCAuNzc0IDAgMS43Mjl2MjAuNTQyQzAgMjMuMjI3Ljc5MiAyNCAxLjc3MSAyNGgyMC40NTFDMjMuMiAyNCAyNCAyMy4yMjcgMjQgMjIuMjcxVjEuNzI5QzI0IC43NzQgMjMuMiAwIDIyLjIyMiAwaC4wMDN6Ii8+PC9zdmc+"/></a> &nbsp;
<a href="mailto:ivan.bioli@gmail.com"><img alt="Email" src="https://img.shields.io/badge/-ivan.bioli@gmail.com-0B1A33?style=flat&logo=gmail&logoColor=EA4335"/></a>

## 👨🏻‍💻 About me

💡 &nbsp; I build efficient, mathematically grounded solvers, from the model to tested code that runs fast.\
🎓 &nbsp; Marie Skłodowska-Curie Doctoral Fellow at the **University of Pavia** (IN-DEEP European Doctoral Network), working on **deep learning for PDEs** and **inverse problems** in computational oncology. MSc in Computational Science and Engineering at **EPFL**, BSc in Mathematics at the **University of Pisa**.\
🏎️ &nbsp; Previously: reinforcement learning for live race strategy at the **Alfa Romeo F1 Team**.\
🤝 &nbsp; **Open to collaborations in research and industry:** simulation, surrogate modelling, optimisation and machine learning for engineering and scientific problems.

## 🔬 What I work on

- **Scientific machine learning:** neural PDE solvers, physics-informed training, optimisers for neural networks
- **Numerical PDEs:** finite elements and isogeometric analysis, discretisation and error analysis
- **Inverse problems and UQ:** Bayesian inversion and model calibration with neural surrogates
- **Numerical linear algebra:** low-rank methods, Riemannian optimisation, randomised preconditioning

## 📦 Selected code

| Project | What it is | Paper |
|---|---|---|
| [**ssbroyden-optimistix**](https://github.com/IvanBioli/ssbroyden_optimistix) [![PyPI](https://img.shields.io/pypi/v/ssbroyden-optimistix?style=flat&label=PyPI&color=0B1A33)](https://pypi.org/project/ssbroyden-optimistix/) | Quasi-Newton minimisers for JAX, as an add-on to [Optimistix](https://github.com/patrick-kidger/optimistix): the self-scaled Broyden family (SSBroyden, SSBFGS, SSDFP), BFGS, DFP and L-BFGS, with a strong-Wolfe Zoom line search. `pip install ssbroyden-optimistix` | [arXiv:2603.10599](https://doi.org/10.48550/arXiv.2603.10599) |
| [**randngd**](https://github.com/IvanBioli/preconditioned-natural-gradient) [![PyPI](https://img.shields.io/pypi/v/randngd?style=flat&label=PyPI&color=0B1A33)](https://pypi.org/project/randngd/) | Natural gradient descent for neural PDE solvers, with matrix-free CG and randomized (Nyström, RPCholesky) preconditioners, built on JAX and Optimistix. `pip install randngd` | *CMAME* (to appear) · [arXiv:2505.11638](https://arxiv.org/abs/2505.11638) |
| [**TT_for_GPE**](https://github.com/IvanBioli/TT_for_GPE) | Riemannian optimisation on low-rank tensor-train manifolds for Gross–Pitaevskii ground states | [arXiv:2609.37103](https://arxiv.org/abs/2609.37103) |
| [**ldnets-tumor-inversion**](https://github.com/IvanBioli/ldnets-tumor-inversion) | Latent-dynamics surrogates for uncertainty-aware Bayesian inversion of tumor growth models | in preparation |
| [**riemannian-spdmatrixeq**](https://github.com/IvanBioli/riemannian-spdmatrixeq) | Preconditioned low-rank Riemannian optimisation for SPD linear matrix equations | [*SISC* 47(2), 2025](https://doi.org/10.1137/24M1680429) |

## 🛠️ Open-source contributions

- [patrick-kidger/optimistix](https://github.com/patrick-kidger/optimistix): fix of the sign of the Hestenes–Stiefel and Dai–Yuan β in nonlinear conjugate gradient ([#241](https://github.com/patrick-kidger/optimistix/pull/241), under review)
- [JuliaNLSolvers/Optim.jl](https://github.com/JuliaNLSolvers/Optim.jl): fix to preconditioner updates in nonlinear conjugate gradient (merged)
- [NicolasBoumal/manopt](https://github.com/NicolasBoumal/manopt): new β-update rules for Riemannian conjugate gradient, after Sato (merged)

## 🧑‍🏫 Teaching

- [**elementifiniti2526**](https://github.com/IvanBioli/elementifiniti2526): exercise material in Julia for the *Finite Elements* course at the University of Pavia (in Italian)
- Lecturer of *Introduction to Julia Programming for Data Science and Scientific Computing*, University of Pavia

## 💻 Tech stack

#### Programming languages

[![Python](https://img.shields.io/badge/-Python-0B1A33?style=flat&logo=python)](https://www.python.org/) &nbsp;
[![Julia](https://img.shields.io/badge/-Julia-0B1A33?style=flat&logo=julia)](https://julialang.org/) &nbsp;
[![MATLAB](https://img.shields.io/badge/-MATLAB-0B1A33?style=flat&logo=mathworks&logoColor=E16737)](https://www.mathworks.com/products/matlab.html) &nbsp;
[![C++](https://img.shields.io/badge/-C++-0B1A33?style=flat&logo=cplusplus&logoColor=659AD2)](https://isocpp.org/)

#### Machine learning and scientific computing

[![JAX](https://img.shields.io/badge/-JAX-0B1A33?style=flat&logo=google)](https://docs.jax.dev/) &nbsp;
[![PyTorch](https://img.shields.io/badge/-PyTorch-0B1A33?style=flat&logo=pytorch)](https://pytorch.org/) &nbsp;
[![TensorFlow](https://img.shields.io/badge/-TensorFlow-0B1A33?style=flat&logo=tensorflow)](https://www.tensorflow.org/) &nbsp;
[![NumPy](https://img.shields.io/badge/-NumPy-0B1A33?style=flat&logo=numpy&logoColor=4DABCF)](https://numpy.org/) &nbsp;
[![SciPy](https://img.shields.io/badge/-SciPy-0B1A33?style=flat&logo=scipy&logoColor=8CAAE6)](https://scipy.org/) &nbsp;
[![CUDA](https://img.shields.io/badge/-CUDA-0B1A33?style=flat&logo=nvidia)](https://developer.nvidia.com/cuda-toolkit)

#### Tools

[![Git](https://img.shields.io/badge/-Git-0B1A33?style=flat&logo=git)](https://git-scm.com/) &nbsp;
[![GitHub](https://img.shields.io/badge/-GitHub-0B1A33?style=flat&logo=github)](https://github.com/) &nbsp;
[![LaTeX](https://img.shields.io/badge/-LaTeX-0B1A33?style=flat&logo=latex&logoColor=white)](https://www.latex-project.org/) &nbsp;
[![Overleaf](https://img.shields.io/badge/-Overleaf-0B1A33?style=flat&logo=overleaf)](https://www.overleaf.com/)

---

<sub>Publications, talks and CV: <a href="https://ivanbioli.github.io">ivanbioli.github.io</a></sub>
