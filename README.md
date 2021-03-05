# GP-Multilang
Multi-language Gaussian Processes codes, intended as a comprehensive learning material for core concepts with multiple programming languages

This repository is intended for writing Gaussian Process codes, starting with a very simple 1D version and extending it bit by bit with useful fitting options, including sum and gradient observations, sparsification, etc. I intend to look into solvers and how parallel execution is possible on various languages.

Initially I will implement it in Python, using NumPy mainly and then accelerate that in various ways, for example with Numba and later with JAX and TensorFlow. 

Later on, I am planning to write the same code with multiple languages:
- [ ] Julia
- [ ] Fortran
- [ ] C++
- [ ] OCaml
Which should serve as a way of learning the quirks of these languages and their parallel capabilities. 

## Roadmap for GP
- GP 1D - follow documentaton/example, maybe in autograd actually
- GP 2D dot-product
- GP any kernel between vectors
- GP ND -> scalar observation
- GP with sum-observations
- GP with gradient observations
- combine all of these
- sparse GP

