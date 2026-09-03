---
short_title: Attractor networks
---

% add an empty header to avoid having the first header in the page repeat twice
##

## Large-scale brain attractor networks

We work on a **scale-free, first-principles** computational model of large-scale brain dynamics. The framework links **connectivity to activity** and can disentangle network-level computations at a given level of description (imaging modality and parcellation) from **intrinsic** computations and activity at lower levels — including sensory inputs and recurrent low-level processing.

```{image} ../figures/projects/attractor-framework.jpg
:alt: A scale-free framework of biologically plausible attractor nets
:width: 100%
:align: center
```

### Approach

Starting from the Free Energy Principle applied to deep particular partitions, attractor networks emerge without hand-crafted learning or inference rules. Attractors on the free-energy landscape act as Bayesian priors; inference integrates data into posteriors; learning tunes couplings to reduce long-term surprise. A hallmark is **self-orthogonalization**: approximately orthogonal attractor representations that efficiently span the input subspace.

Mapped to neuroimaging, resting-state and task fMRI can be fit (e.g. via score matching) onto connectivity-based attractor networks. Resting-state networks appear as approximate attractors; task dynamics can be read as Bayesian inference in which **weights** capture network-level dynamics and **biases** capture upstream / mesoscale drive. Clinical states (e.g. acute vs chronic pain) can be framed as changes in landscape geometry — shallow vs deep, trapping wells.

### Key publications & resources

- Spisak & Friston — *Self-orthogonalizing attractor neural networks emerging from the free energy principle*  
  [Neurocomputing](https://doi.org/10.1016/j.neucom.2026.133472) · [Manuscript site](https://pni-lab.github.io/fep-attractor-network/) · [ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0925231226008696)

- Englert et al. — *Functional Connectivity-based Attractor Dynamics in Rest, Task, and Disease*  
  [eLife](https://doi.org/10.7554/eLife.98725) · [connattractor site](https://pni-lab.github.io/connattractor) · [GitHub](https://github.com/pni-lab/connattractor)

### Software

- **[connattractor](../06-software.md)** — connectome-based Hopfield / attractor analyses for fMRI (`pip install connattractor`)
- **[attractome](https://github.com/pni-lab/attractome)** — connectivity-based FEP attractor nets for parcellated fMRI (HRF deconvolution, score matching, attractor utilities; research preview)

See also [Brain models / fcHNN](../05-brain-models.md#fchnn) and [Publications](../04-publications.md).
