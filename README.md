Master’s Thesis Project by Belguutei Ariuntugs

A unified framework for high‑resolution interpolation and extrapolation of environmental variables using sparse Gaussian processes (nearest‑neighbor spatio‑temporal kriging) combined with graph neural networks (GNN).

Key features:

  Non‑separable covariance modeling: Implements a flexible covariance function for space‑time data.

  Nearest‑neighbor kriging: Scales Gaussian process inference by selecting m nearest neighbors via covariance ranking.

  Dynamic graph construction: Builds a sparse adjacency matrix from fitted spatial covariance at each time step.

  Hybrid GNN architecture: Integrates kriging predictions as skip connections into a GraphWaveNet model for multi‑step forecasting.

  Benchmarking: Achieves 99.9% reduction in computation and 72% accuracy gain over baseline methods.
