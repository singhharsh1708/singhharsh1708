<h1 align="center">Harsh Singh</h1>

<p align="center"><i>Numerical software. Time integration, solver internals, and the occasional tool.</i></p>

<p align="center">
Google Summer of Code 2026 at <a href="https://sciml.ai/">SciML</a>, under NumFOCUS.<br>
Research with the Chair of Computational Mathematics, TU Hamburg, and the Numerical Analysis Group, Oxford.<br>
375+ merged pull requests to projects maintained by others, 214 of them in SciML.
</p>

<p align="center">
<a href="https://singhharsh.in">Portfolio</a> &nbsp;·&nbsp;
<a href="https://www.linkedin.com/in/harsh-s-08691222a/">LinkedIn</a> &nbsp;·&nbsp;
<a href="https://codeforces.com/profile/hs1663531">Codeforces</a>
</p>

<p align="center">❦</p>

> *The purpose of computing is insight, not numbers.*
> <br>Richard W. Hamming, *Numerical Methods for Scientists and Engineers*, 1962

---

### I. Written and maintained

- **[PETScDiffEq.jl](https://github.com/SciML/PETScDiffEq.jl)** - PETSc's TS time integrators behind the SciML `solve` interface: explicit RK, Rosenbrock-W, BDF, Gauss IRK, ARK IMEX and DAE solvers, with PETSc's discrete adjoint for sensitivities. Registered in General, and the package I spend most maintenance time on.
- **[scrollcraft](https://github.com/singhharsh1708/scrollcraft)** - scroll-animation site builder. Launched as a paid SaaS, since made free and open source; also a Claude Code plugin.
- **[kitbash](https://github.com/singhharsh1708/kitbash)** - one open format for AI agent skills, compiled to ten coding agents, with the standing token cost of each output measured at build time. On npm and Homebrew.
- **[Assay.jl](https://github.com/singhharsh1708/Assay.jl)** - Bayesian inference from first principles: MCMC, SMC and ADVI implemented rather than imported, with the SBC and Geweke checks that prove the numbers are right.

---

### II. SciML and the Julia ecosystem

- **[OrdinaryDiffEq.jl](https://github.com/SciML/OrdinaryDiffEq.jl)** - the ODE, DAE and DDE time integrators, and where most of my work lives. The spectral deferred correction family with adaptive steps and the MIN-SR diagonal sweepers, the explicit MRI-GARK multirate methods, the order-10 MSRK10 tableau, and correctness fixes across the Rosenbrock, FIRK and ESDIRK solvers.
- **[SciMLBenchmarks.jl](https://github.com/SciML/SciMLBenchmarks.jl)** - eight index-2 and index-3 DAE benchmarks from the Bari test set, funded by the SciML Small Grants Program, plus work-precision runs for the multirate and stiff families.
- **[PETSc.jl](https://github.com/JuliaParallel/PETSc.jl)** - wrapper fixes found while building PETScDiffEq.jl.
- Elsewhere in the stack: [ExponentialUtilities.jl](https://github.com/SciML/ExponentialUtilities.jl), [ModelingToolkit.jl](https://github.com/SciML/ModelingToolkit.jl), [SciMLOperators.jl](https://github.com/SciML/SciMLOperators.jl), [NonlinearSolve.jl](https://github.com/SciML/NonlinearSolve.jl), [LinearSolve.jl](https://github.com/SciML/LinearSolve.jl), [SciMLSensitivity.jl](https://github.com/SciML/SciMLSensitivity.jl), [DiffEqNoiseProcess.jl](https://github.com/SciML/DiffEqNoiseProcess.jl), [SciMLBase.jl](https://github.com/SciML/SciMLBase.jl), [Documenter.jl](https://github.com/JuliaDocs/Documenter.jl), [EvoTrees.jl](https://github.com/Evovest/EvoTrees.jl), [SymbolicRegression.jl](https://github.com/astroautomata/SymbolicRegression.jl) and [ArrayInterface.jl](https://github.com/JuliaArrays/ArrayInterface.jl).

---

### III. Beyond Julia

- **[omi](https://github.com/BasedHardware/omi)** - the open-source AI wearable. Crash and data-loss fixes in the app, from wiped SD card recordings to decoders that one bad entry could take down, and the [bot](https://github.com/BasedHardware/omi-vector-bot) that runs its community support queue.
- **[Pasteur Labs](https://github.com/pasteurlabs)** - [Tesseract](https://github.com/pasteurlabs/tesseract-core) with its [PyTorch](https://github.com/pasteurlabs/tesseract-torch) and [JAX](https://github.com/pasteurlabs/tesseract-jax) bindings, and [Mosaic](https://github.com/pasteurlabs/mosaic): dtype checks at the runtime boundary, gradients through list-valued fields, and adjoints for FEniCS solvers.
- **[ZoneMinder](https://github.com/ZoneMinder/zoneminder)** - output escaping, accessibility, PHP 9 forward-compatibility and schema fixes in the video surveillance stack.
- **[Irksome](https://github.com/firedrakeproject/Irksome)** - Runge-Kutta time stepping for finite element problems in Firedrake, with Oxford's Numerical Analysis Group.
- **[openpilot](https://github.com/commaai/openpilot)** - comma.ai's driver assistance system. Its test runner was skipping every parameterized test class; now they run.
- **[tt-metal](https://github.com/tenstorrent/tt-metal)** - Tenstorrent's kernel stack. The ttnn kernel sources that shipped missing from the package, experimental ops included.
- **[Music Blocks](https://github.com/sugarlabs/musicblocks)** - Sugar Labs' visual music programming environment for children.
- **Cloud native** - [apiserver-network-proxy](https://github.com/kubernetes-sigs/apiserver-network-proxy) (Kubernetes SIG) and [Meshery](https://github.com/meshery/meshery).

---

### IV. Writing

- [GSoC 2026 final report](https://singhharsh1708.github.io/gsoc_blog/blog/final-report.html) - what a summer of tableau-ification and multirate integrators actually produced.
- [singhharsh.in](https://singhharsh.in) - notes on numerical methods, open source, and the things I build.
