scikit-learn-JAX
================
This project aims to implement scikit-learn_ using JAX_ allowing for calculating
gradients automatically and XLA (Accelerated Linear Algebra).

Why JAX?
========
* JAX functions can be JIT compiled allowing advanced optimizations.
* JAX support Automatic differentiation out of the box both forward-mode and
  backward-mode.
* JAX follow functional style (NO SIDE EFFECTS!) and immutable arrays.
* JAX allow to parallelize algorithms easily and computation can be done at
  CPU's, GPU's and TPU's

.. _scikit-learn: https://github.com/scikit-learn/scikit-learn
.. _JAX: https://github.com/google/jax

