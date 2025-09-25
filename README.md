# Morphologies of a sagging elastica with intrinsic sensing and actuation

## Series Solutions for Sagging Elastica with Intrinsic Sensing and Actuation

This repository contains Mathematica notebooks implementing the **series solution** described in the article *Morphologies of a sagging elastica with intrinsic sensing and actuation*.  
The work investigates the equilibrium shapes of a slender elastica under gravity when augmented with **intrinsic sensing and distributed actuation**. The feedback strategy is modeled via convolution with Gaussian kernels, and both **local** and **nonlocal** sensing/actuation regimes are considered.  

The series solutions provide **semi-analytical benchmarks** for the elastica problem under weak nonlinearity, complementing the numerical spectral collocation methods also developed in the article.  

---

## Contents

- `SeriesSolutionNSLA.nb`
  Mathematica notebook for the **nonlocal sensing (Gaussian kernel) with local actuation case**.  
  - Expands the integro-differential equation in the sine basis.  
  - Constructs a linear system for coefficients `{a_n}` that is solved numerically.  
  - Demonstrates how kernel width `W` and actuation gain `A` modify the elastica shape.  

---

## Reference

If you use these notebooks, please cite:

> Mishra, V. D. & Prasath, S. G. (2025). *Morphologies of a sagging elastica with intrinsic sensing and actuation*. arXiv:2509.17572
