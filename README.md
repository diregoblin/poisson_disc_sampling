# Poisson disc sampling
Poisson disc sampling in arbitrary dimensions using Bridson's algorithm, implemented in python using ``numpy`` and ``scipy``.

Generates so-called "blue noise" that prevents clustering by ensuring each two points are at least ``radius`` apart.

https://www.cs.ubc.ca/~rbridson/docs/bridson-siggraph07-poissondisk.pdf

Implementation is located in ``bridson.py``, while ``poisson_disc_sampling.ipynb`` contains some examples. 