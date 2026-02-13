Computational Engineer · Lausanne, Switzerland

PhD in mechanics, 8+ years building high-performance numerical software at scale. Currently at EPFL building coupled flow-thermal solvers for conjugate heat transfer with PyTorch/JAX backends for gradient-based optimization. I port proven algorithms into modern, safe implementations (Rust, Modern Fortran) and build agentic engineering workflows.

## Fortran

- [nekStab](https://github.com/nekStab/nekStab) — Stability analysis toolbox for Nek5000: linear/adjoint solvers, Newton-GMRES for UPOs, eigensolvers, native POD/SPOD/DMD. Scaled to 10,000+ cores.
- [LightKrylov](https://github.com/nekStab/LightKrylov) — Standalone Krylov methods library: Arnoldi, Lanczos, GMRES, SVD. Published in [JOSS](https://joss.theoj.org/papers/10.21105/joss.09623).
- [Xcompact3d](https://github.com/xcompact3d/Incompact3d) — MPI-parallel Navier-Stokes solver for turbulence research.
- [dNami](https://github.com/dNamiLab/dNami) — Compressible flow framework with Python→Fortran codegen for compute-critical kernels.

## Python

- [dolfinx-rans](https://github.com/ricardofrantz/dolfinx-rans) — Standalone RANS k-omega solver in FEniCSx with conjugate heat transfer.
- [pyModal](https://github.com/ricardofrantz/pyModal) — Modal decomposition toolkit: POD, DMD, SPOD, ST-POD, bispectral analysis. Multiple FFT backends (MKL, Accelerate, CuPy, PyTorch).
- [dsgbr](https://github.com/ricardofrantz/dsgbr) — Spectral peak detector using dual Savitzky-Golay filtering for PSD signals. Published on [PyPI](https://pypi.org/project/dsgbr/).

## Rust

- [nanobook](https://github.com/ricardofrantz/nanobook) — Trading engine: order book matching at ~120 ns/order, portfolio optimization, IBKR/Binance adapters.
- [nanochat-rs-next](https://github.com/ricardofrantz/nanochat-rs-next) — Rust CLI for training tiny language models, benchmarked against karpathy/nanochat.
- [minuit2-rs](https://github.com/ricardofrantz/minuit2-rs) — CERN's Minuit2 rewritten in pure Rust, zero unsafe, Python bindings. Verified against ROOT.
- [libsvm-rs](https://github.com/ricardofrantz/libsvm-rs) — LIBSVM rewritten in pure Rust. All SVM types/kernels, 250-config test suite, ~1e-8 parity.

## Web

- [chaos-atlas](https://github.com/ricardofrantz/chaos-atlas) — Interactive chaos explorer: bifurcation diagrams, Lyapunov exponents, strange attractors across 10 maps. [Live demo](https://ricardofrantz.github.io/chaos-atlas/).
- [chaosviz](https://chaosviz.vercel.app/) — Browser-based chaotic attractor visualizer (Lorenz, Rössler, and more).
- [coinscope](https://ricardofrantz.github.io/coinscope/) — Crypto analysis dashboard with live CoinGecko data and technical indicators.
- [sacred-timeline](https://ricardofrantz.github.io/sacred_timeline/) — Chronological database from the Big Bang to present in a TVA terminal aesthetic.

## Plugin

- [fortran-lsp](https://github.com/ricardofrantz/fortran-lsp) — Claude Code plugin for Fortran diagnostics, navigation, and refactoring via fortls.

## Publications

- [LightKrylov: Lightweight Krylov subspace techniques in modern Fortran](https://joss.theoj.org/papers/10.21105/joss.09623), *JOSS*, 2026
- [Bifurcation sequence in the wakes of a sphere and a cube](https://www.cambridge.org/core/journals/journal-of-fluid-mechanics/article/bifurcation-sequence-in-the-wakes-of-a-sphere-and-a-cube/FD3454216F8CDCD9F6CCDA3ECCB78EBA), *J. Fluid Mech.*, 2025
- [Asymptotic scaling laws for periodic turbulent boundary layers up to Re_θ = 8300](https://doi.org/10.1017/jfm.2025.10578), *J. Fluid Mech.*, 2025
- [Krylov Methods for Large-Scale Dynamical Systems: Application in Fluid Dynamics](https://doi.org/10.1115/1.4056808), *Appl. Mech. Rev.*, 2023
- [High-fidelity simulations of gravity currents using spectral vanishing viscosity](https://doi.org/10.1016/j.compfluid.2021.104902), *Comput. & Fluids*, 2021
- [Xcompact3D: An open-source framework for solving turbulence problems](https://doi.org/10.1016/j.softx.2020.100550), *SoftwareX*, 2020

Full list: [Google Scholar](https://scholar.google.com/citations?user=VzovS2oAAAAJ&hl=en)

## Links

[Website](https://ricardofrantz.github.io) · [LinkedIn](https://www.linkedin.com/in/rfrantz91) · [YouTube](https://www.youtube.com/channel/UC9quHxfzJkrFXQnI2DF2Jsw) · [ResearchGate](https://www.researchgate.net/profile/Ricardo-Frantz) · [Unsplash](https://unsplash.com/@ricardofrantz)
