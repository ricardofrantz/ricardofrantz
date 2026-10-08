**Computational Engineer**

Numerical software: models, solvers and the tools around them. Topics include automatic differentiation (tangent-linear and adjoint), PDE-constrained and surrogate-based optimization, and signal and data analysis, applied to PDE solver generation, lattice Boltzmann methods and quantitative trading systems. The code runs on CPUs, GPUs (CUDA kernels) and HPC clusters, in Rust, Python and Fortran.

Other projects: ports of established libraries to Rust with verified parity, and developer tools (VS Code extensions, desktop apps, Claude Code plugins).

**Organizations** · [openfluids](https://github.com/openfluids) · [BoringQuantSystems](https://github.com/BoringQuantSystems) · [brachistos](https://github.com/brachistos) · [nekStab](https://github.com/nekStab)

## Rust

- [nanobook](https://github.com/BoringQuantSystems/nanobook) — Trading engine: order book matching at ~120 ns/order, portfolio optimization, IBKR/Binance adapters. On [crates.io](https://crates.io/crates/nanobook) and [PyPI](https://pypi.org/project/nanobook/).
- [minuit2-rs](https://github.com/ricardofrantz/minuit2-rs) — CERN's Minuit2 rewritten in pure Rust, zero unsafe, Python bindings. Verified against ROOT. On [crates.io](https://crates.io/crates/minuit2).
- [libsvm-rs](https://github.com/ricardofrantz/libsvm-rs) — LIBSVM rewritten in pure Rust. All SVM types/kernels, 250-config test suite, ~1e-8 parity. On [crates.io](https://crates.io/crates/libsvm-rs).
- [nebula-quanta](https://github.com/ricardofrantz/nebula-quanta) — Deterministic Barnes-Hut N-body simulation engine: quadtree spatial decomposition, O(N log N) force approximation.
- [nanochat-rs-next](https://github.com/BoringQuantSystems/nanochat-rs-next) — Rust CLI for training tiny language models, pure-Rust CPU path or CUDA GPUs through libtorch (`tch`), benchmarked against karpathy/nanochat.

## Python

- [linstabpy](https://github.com/openfluids/linstabpy) — Linear stability and resolvent analysis for compressible viscous flows, targeting PETSc/SLEPc for large-scale problems. [Docs](https://linstabpy.vercel.app/).
- [openmodalpy](https://github.com/openfluids/openmodalpy) — Nine modal decompositions behind one interface: POD, MPOD, DMD, SPOD, PSD-POD, BSMD, ST-POD. One data contract, one config file, same result format for every method. On [PyPI](https://pypi.org/project/openmodalpy/).
- [fftkit](https://github.com/openfluids/fftkit) — One FFT API over eight backends (scipy, numpy, MKL, CuPy, PyTorch, TensorFlow, pyFFTW, Accelerate), plus `spectrum()` for PSDs of physical signals. On [PyPI](https://pypi.org/project/fftkit/).
- [dsgbr](https://github.com/openfluids/dsgbr) — Spectral peak detector using dual Savitzky-Golay filtering for PSD signals. Published on [PyPI](https://pypi.org/project/dsgbr/).
- [organa](https://github.com/brachistos/organa) — Adjoint-based topology optimization for microfluidic cooling: Brinkman-NS + CHT on Firedrake/pyadjoint with GCMMA optimizer.
- [dolfinx-rans](https://github.com/brachistos/dolfinx-rans) — Standalone RANS k-omega solver in FEniCSx with conjugate heat transfer.
- [dynachaos](https://github.com/openfluids/dynachaos) — Dynamical-systems analysis of time signals: Lyapunov exponents, recurrence quantification, entropy, correlation dimension, multifractal spectra. Rust kernels with Python fallbacks. On [PyPI](https://pypi.org/project/dynachaos/).
  - Site: [From Locking to Collective Chaos](https://openfluids.github.io/dynachaos/), a reproducible review of Kaneko-style coupled-map systems.
- [hpckit](https://github.com/openfluids/hpckit) — CLI for Slurm workflows from a local checkout: remote tool checkouts, per-commit virtualenvs, job submission and polling, artifact sync, run records. On [PyPI](https://pypi.org/project/hpckit/).
- [quadros](https://github.com/openfluids/quadros) — Renders simulation snapshots (Nek5000 and others, via PyVista) into checked frame sets and videos, locally, over SSH or in Slurm jobs. On [PyPI](https://pypi.org/project/quadros/).
- [slendr](https://github.com/ricardofrantz/slendr) — Thermal fiber drawing solver: Chebyshev spectral, shooting method, discrete adjoint. SciPy/PyTorch/JAX backends.

## Tools

- [pdf-next](https://github.com/ricardofrantz/pdf-next) — Desktop PDF, image and Markdown viewer that reloads the moment the file changes, built for the LaTeX/Typst compile loop. Rust + PDF.js. Installers for Windows, macOS (Homebrew) and Debian/Ubuntu.
- [vscode-pdf Next](https://github.com/ricardofrantz/vscode-pdf-next) — VS Code PDF viewer, successor to `tomoki1207.vscode-pdf`: PDF.js 6, dark reading modes, live reload that keeps page and zoom, search, outline. On the [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=RicardoFrantz.pdf-preview-next).
- [vscode-diff Next](https://github.com/ricardofrantz/vscode-diff-next) — VS Code extension to compare two branches, or branches of two different repos in one workspace: changed-file tree, commit history, built-in diffs. Successor to Diff Visualizer. On the [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=RicardoFrantz.diff-next).
- [fortran-lsp](https://github.com/ricardofrantz/fortran-lsp) — Claude Code plugin for Fortran diagnostics, navigation, and refactoring via fortls.
- [pi-effort](https://github.com/ricardofrantz/pi-effort) — Extension for the pi coding agent: `/effort` and `/fast` commands to set reasoning effort and fast mode. On [npm](https://www.npmjs.com/package/pi-effort).

## Web

- [chaos-atlas](https://github.com/openfluids/chaos-atlas) — Interactive chaos explorer: bifurcation diagrams, Lyapunov exponents, strange attractors across 10 maps. [Live demo](https://openfluids.github.io/chaos-atlas/).
- [chaosviz](https://chaosviz.vercel.app/) — Browser-based chaotic attractor visualizer (Lorenz, Rössler, and more).
- [coinscope](https://ricardofrantz.github.io/coinscope/) — Crypto analysis dashboard with live CoinGecko data and technical indicators.
- [sacred-timeline](https://ricardofrantz.github.io/sacred_timeline/) — Chronological database from the Big Bang to present in a TVA terminal aesthetic.
- [bun-do](https://github.com/ricardofrantz/bun-do) — Fast local-first todo app: Bun + Alpine.js, zero dependencies, JSON storage. On [npm](https://www.npmjs.com/package/bun-do).

## Fortran

- [nekStab](https://github.com/nekStab/nekStab) — Stability analysis toolbox for Nek5000: linear/adjoint solvers, Newton-GMRES for UPOs, eigensolvers, native POD/SPOD/DMD. Scaled to 10,000+ cores.
- [LightKrylov](https://github.com/nekStab/LightKrylov) — Standalone Krylov methods library: Arnoldi, Lanczos, GMRES, SVD. Published in [JOSS](https://joss.theoj.org/papers/10.21105/joss.09623).
- [Xcompact3d](https://github.com/xcompact3d/Incompact3d) — MPI-parallel Navier-Stokes solver for turbulence research.
- [dNami](https://github.com/dNamiLab/dNami) — Compressible flow framework with Python→Fortran codegen for compute-critical kernels.

## Publications

- [LightKrylov: Lightweight Krylov subspace techniques in modern Fortran](https://joss.theoj.org/papers/10.21105/joss.09623), *JOSS*, 2026
- [Bifurcation sequence in the wakes of a sphere and a cube](https://www.cambridge.org/core/journals/journal-of-fluid-mechanics/article/bifurcation-sequence-in-the-wakes-of-a-sphere-and-a-cube/FD3454216F8CDCD9F6CCDA3ECCB78EBA), *J. Fluid Mech.*, 2025
- [Asymptotic scaling laws for periodic turbulent boundary layers up to Re_θ = 8300](https://doi.org/10.1017/jfm.2025.10578), *J. Fluid Mech.*, 2025
- [Krylov Methods for Large-Scale Dynamical Systems: Application in Fluid Dynamics](https://doi.org/10.1115/1.4056808), *Appl. Mech. Rev.*, 2023
- [High-fidelity simulations of gravity currents using spectral vanishing viscosity](https://doi.org/10.1016/j.compfluid.2021.104902), *Comput. & Fluids*, 2021
- [Xcompact3D: An open-source framework for solving turbulence problems](https://doi.org/10.1016/j.softx.2020.100550), *SoftwareX*, 2020

Full list: [Google Scholar](https://scholar.google.com/citations?user=VzovS2oAAAAJ&hl=en)

## Links

[LinkedIn](https://www.linkedin.com/in/rfrantz91) · [YouTube](https://www.youtube.com/channel/UC9quHxfzJkrFXQnI2DF2Jsw) · [ResearchGate](https://www.researchgate.net/profile/Ricardo-Frantz) · [Unsplash](https://unsplash.com/@ricardofrantz)
