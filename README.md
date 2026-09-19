<h1 align="center">Harsh Singh</h1>

<p align="center">
Numerical methods and scientific computing, mostly in Julia.<br>
Google Summer of Code 2026 contributor at <a href="https://sciml.ai/">SciML</a>, under NumFOCUS.<br>
240+ merged pull requests across the projects below.
</p>

<p align="center">
<a href="https://singhharsh.in">Portfolio</a> &nbsp;·&nbsp;
<a href="https://www.linkedin.com/in/harsh-s-08691222a/">LinkedIn</a> &nbsp;·&nbsp;
<a href="https://codeforces.com/profile/hs1663531">Codeforces</a>
</p>

<table>
<tr>
<td valign="top" width="33%">

### What I build

- [PETScDiffEq.jl](https://github.com/SciML/PETScDiffEq.jl) - PETSc's TS time integrators behind the SciML `solve` interface: explicit RK, Rosenbrock-W, BDF, Gauss IRK, ARK IMEX and DAE solvers. I wrote it and maintain it; it is registered in General.
- [scrollcraft](https://github.com/singhharsh1708/scrollcraft) - AI scroll-website builder: a hosted app, plus a Claude Code skill you install with `/plugin marketplace add`.
- [kitbash](https://github.com/singhharsh1708/kitbash) - package manager and compiler for AI agent skills. Write a skill once, run it in Claude Code, Cursor, Codex, Copilot and Gemini CLI.
- [Assay.jl](https://github.com/singhharsh1708/Assay.jl) - Bayesian inference from first principles: MCMC, SMC and ADVI implemented rather than imported, with the SBC and Geweke checks that prove the numbers are right.

### Writing

- [GSoC 2026 final report](https://singhharsh1708.github.io/gsoc_blog/blog/final-report.html) - what a summer of tableau-ification and multirate integrators actually produced.

</td>
<td valign="top" width="33%">

### SciML and Julia

- [OrdinaryDiffEq.jl](https://github.com/SciML/OrdinaryDiffEq.jl) - the ODE time integrators, and where most of my work lives. I added the spectral deferred correction family with adaptive steps and the MIN-SR diagonal sweepers, the explicit MRI-GARK multirate methods and the order-10 MSRK10 tableau, along with correctness fixes across the Rosenbrock, FIRK and ESDIRK solvers.
- [SciMLBenchmarks.jl](https://github.com/SciML/SciMLBenchmarks.jl) - work-precision benchmarks for the multirate and stiff solver families.
- [PETSc.jl](https://github.com/JuliaParallel/PETSc.jl) - wrapper fixes found while building PETScDiffEq.jl.
- Smaller fixes in [ModelingToolkit.jl](https://github.com/SciML/ModelingToolkit.jl), [SciMLOperators.jl](https://github.com/SciML/SciMLOperators.jl), [NonlinearSolve.jl](https://github.com/SciML/NonlinearSolve.jl) and [SciMLBase.jl](https://github.com/SciML/SciMLBase.jl).
- Across the wider ecosystem: [Documenter.jl](https://github.com/JuliaDocs/Documenter.jl), [EvoTrees.jl](https://github.com/Evovest/EvoTrees.jl), [SymbolicRegression.jl](https://github.com/astroautomata/SymbolicRegression.jl) and [ArrayInterface.jl](https://github.com/JuliaArrays/ArrayInterface.jl).

</td>
<td valign="top" width="33%">

### Beyond Julia

- **[Pasteur Labs](https://github.com/pasteurlabs)** - [Tesseract](https://github.com/pasteurlabs/tesseract-core) with its [PyTorch](https://github.com/pasteurlabs/tesseract-torch) and [JAX](https://github.com/pasteurlabs/tesseract-jax) bindings, and [Mosaic](https://github.com/pasteurlabs/mosaic): dtype checks at the runtime boundary, gradients through list-valued fields, and adjoints for FEniCS solvers.
- **[ZoneMinder](https://github.com/ZoneMinder/zoneminder)** - accessibility, PHP 9 forward-compatibility and build fixes in the video surveillance stack.
- **[omi](https://github.com/BasedHardware/omi)** - crash and data-loss fixes in the app for the open-source AI wearable: SD card and offline recordings that got wiped, and decoders that one bad entry could take down.
- **[openpilot](https://github.com/commaai/openpilot)** - comma.ai's driver assistance system. Its test runner was skipping every parameterized test class; now they run.
- **[Music Blocks](https://github.com/sugarlabs/musicblocks)** - Sugar Labs' visual music programming environment for children.
- **[Irksome](https://github.com/firedrakeproject/Irksome)** - Runge-Kutta time stepping for Firedrake.
- **Cloud native** - [apiserver-network-proxy](https://github.com/kubernetes-sigs/apiserver-network-proxy) (Kubernetes SIG) and [Meshery](https://github.com/meshery/meshery).

</td>
</tr>
</table>
