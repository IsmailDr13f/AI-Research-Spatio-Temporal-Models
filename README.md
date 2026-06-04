<h1 align="center">AI Research: Spatio-Temporal Models</h1>

<p align="center">
  A dedicated hub for exploring, building, and advancing Spatio-Temporal Models. This repository acts as a living collection of our ongoing AI research, focusing primarily on deep learning approaches for Spatio-Temporal Point Processes (STPP). By bringing together novel paradigms, scalable implementations, and cutting-edge experimentation tools, we aim to push the boundaries of how we understand and predict complex events that unfold across both time and space—whether it's forecasting traffic, tracking disease spread, or predicting seismic activity.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/last_commit-recent-brightgreen" alt="last commit">
  <img src="https://img.shields.io/badge/branch-main-blue" alt="branch">
  <img src="https://img.shields.io/badge/issues-0_open-yellow" alt="issues">
  <img src="https://img.shields.io/badge/license-MIT-blue" alt="license">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/python-3.10+-blue?logo=python&logoColor=white" alt="python">
  <img src="https://img.shields.io/badge/pytorch-2.0+-ee4c2c?logo=pytorch&logoColor=white" alt="pytorch">
  <img src="https://img.shields.io/badge/lightning-2.0+-792de4?logo=pytorchlightning&logoColor=white" alt="lightning">
  <img src="https://img.shields.io/badge/aim-3.17+-00b0f0?logo=aim&logoColor=white" alt="aim">
</p>

---

## Table of Contents

| [About](#about) | [Current Projects](#current-projects) | [Future Roadmap](#future-roadmap) | [Tech Stack](#tech-stack) | [Getting Started](#getting-started) | [License](#license) |

---

## About
Spatio-temporal modeling is all about making sense of the "when" and "where". In the real world, data rarely sits still. Events happen in a specific sequence and at specific locations. Our goal here is to consolidate robust, research-grade code that tackles these challenges head-on. Expect to find implementations that are not just theoretical, but designed to be scalable and efficient for real-world event streaming.

## Current Projects
We are currently incubating the following research:

- **[AutoSTPP](./AutoSTPP/)**: A fresh take on exact, efficient, non-parametric inference for spatiotemporal point processes. It introduces the *Automatic Integration* paradigm, making complex STPP models much more tractable.

## Future Roadmap
Research never sleeps. Here is what we're planning to bring to this repository next:
- **Graph Neural Networks (GNNs)**: For dynamic forecasting over complex, non-Euclidean networks.
- **Copula-based Architectures**: To better capture intricate, real-world dependencies in event data.
- **Foundation Models**: Scaling up sequence modeling to handle continuous space and time natively.
- **State-Space Models (SSMs)**: Adapting recent advances in SSMs for multidimensional spatio-temporal dynamics.
- **Benchmarks & Datasets**: Curated evaluation suites to standardize how we measure STPP performance.

## Tech Stack
We build with a modern, researcher-friendly stack:
- **Core ML:** PyTorch & PyTorch Lightning
- **Experiment Tracking:** Aim (because keeping track of hyper-parameters shouldn't be a headache)
- **Data & Logging:** NumPy, Pandas, SciPy, Loguru, Torchtyping

## Getting Started
To dive in, check out the individual project folders. Each sub-project (like `AutoSTPP`) comes with its own detailed `README.md`, installation instructions, and quick-start guides.

## License
Most of the work here is open-source. Each sub-project maintains its own licensing (for instance, AutoSTPP uses the MIT License). Please check the respective directories for the fine print.