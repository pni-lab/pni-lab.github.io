---
short_title: Scientific practices
---

% add an empty header to avoid having the first header in the page repeat twice
##

## Scientific discourse & good practices

We care as much about **how** predictive neuroimaging is done as about any single biomarker. This page collects comments, primers, community standards work, and tooling that push for replicability, transparency, and responsible ML in the neurosciences.

### Replicability & predictive modelling

| Paper | Focus |
| --- | --- |
| [Spisak, Bingel & Wager — Multivariate BWAS can be replicable with moderate sample sizes](https://www.nature.com/articles/s41586-023-05745-x) (*Nature*, 2023) | Matters Arising: multivariate brain-wide association studies can replicate with moderate *N* when done carefully. |
| [Kotikalapudi et al. — On the replicability of diffusion weighted MRI-based brain-behavior models](https://www.nature.com/articles/s42003-025-09048-x) (*Commun Biol*, 2025) | How (and when) DWI-based brain–behaviour models replicate. |
| [Goltermann, Spisak & Büchel — Concern About Predictive Performance of a Pain Sensitivity Biomarker](https://doi.org/10.1001/jamaneurol.2025.2351) (*JAMA Neurol*, 2025) | Comment on non-independent “validation” and inflated biomarker performance claims. |

### Primers & community standards

| Paper | Focus |
| --- | --- |
| [Badrulhisham et al. — Machine learning and artificial intelligence in neuroscience: A primer for researchers](https://www.sciencedirect.com/science/article/pii/S0889159123003380) (*Brain Behav Immun*, 2023) | Accessible primer on ML/AI for neuroscientists — strengths, overfitting risks, black-box limits. |
| [Poldrack et al. — The Past, Present, and Future of the Brain Imaging Data Structure (BIDS)](https://direct.mit.edu/imag/article/doi/10.1162/imag_a_00103/119672) (*Imaging Neuroscience*, 2023) | Community perspective on BIDS as infrastructure for open, reusable neuroimaging. |

### Research infrastructure for privacy & open science

| Resource | Focus |
| --- | --- |
| [Englert et al. — ALIIAS](../06-software.md) (*SoftwareX*, 2023) | Customisable anonymization/pseudonymization with LimeSurvey integration and two-factor authentication. |

Related methodological packages for trustworthy predictive models (confound testing, adaptive external validation, cluster enhancement) are listed under [Predictive models](predictive-models.md) and [Software](../06-software.md). See also [BWAS replicability](../06-software.md#bwas-replicability).
