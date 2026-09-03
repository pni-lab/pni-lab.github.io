---
short_title: RLBF
---

% add an empty header to avoid having the first header in the page repeat twice
##

## Reinforcement Learning via Brain Feedback (RLBF)

Traditional fMRI uses fixed paradigms. **RLBF** reverses the usual direction of inference: neural responses guide exploration of a stimulus space via reinforcement learning, so that stimuli can be adapted in real time to optimise a chosen brain target (regional activity or a multivariate signature).

```{image} ../figures/projects/rlbf.png
:alt: Reinforcement Learning via Brain Feedback closed-loop schematic
:width: 80%
:align: center
```

An AI paradigm generator presents a task/stimulus; real-time fMRI yields a neural response that serves as reward feedback for the RL agent, which updates the next stimulus — closing the loop.

### Key publication

[Gallitto et al. — *Reinforcement Learning via Brain Feedback for real-time fMRI-based adaptive stimulus generation*](https://www.biorxiv.org/content/10.64898/2026.08.08.743648v1)

The accompanying Python framework integrates real-time fMRI processing, RL agents, adaptive stimulus generation, simulation testing, and experiment monitoring. In a proof-of-concept (N=10), RLBF adapted checkerboard contrast and frequency within a single ~10-minute session to maximise V1 responses.

### Software

- Current repository: [git.uni-due.de/pnl-lab/rlbf](https://git.uni-due.de/pnl-lab/rlbf) (official)
- Legacy / prototype: [github.com/pni-lab/RLBF](https://github.com/pni-lab/RLBF)
