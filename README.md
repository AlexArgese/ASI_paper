# Dropout as a Bayesian Approximation - Alex Argese's assignment

This repository reproduces and extends the core experiments of **Gal & Ghahramani (2016)**, demonstrating how test-time dropout approximates Bayesian inference by providing meaningful epistemic uncertainty.

## Summary

We train a LeNet-style CNN on MNIST and apply **MC-Dropout** at inference to:

- Measure uncertainty on rotated digits.
- Evaluate robustness with and without data augmentation.
- Test OoD detection using Fashion-MNIST.

All results are automatically generated in the notebook.

## Files

- `argese_paper.ipynb` – main notebook
- `results/` – plots (breaking point, digits STD, etc.)
