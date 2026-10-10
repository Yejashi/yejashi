<div align="center">

<img src="assets/header.svg" width="100%" alt="Befikir T. Bogale — Ph.D. student in Computer Science (HPC) at the University of Tennessee, Knoxville" />

<br />

<a href="https://www.befikirbogale.com/"><img src="https://img.shields.io/badge/website-befikirbogale.com-ff8200?style=flat-square&labelColor=0d1117&logo=googlechrome&logoColor=white" alt="Website" /></a>
<a href="https://www.befikirbogale.com/files/befikir_cv.pdf"><img src="https://img.shields.io/badge/CV-pdf-ff8200?style=flat-square&labelColor=0d1117&logo=readdotcv&logoColor=white" alt="CV" /></a>
<a href="mailto:bbogale@vols.utk.edu"><img src="https://img.shields.io/badge/email-bbogale@vols.utk.edu-2dd4bf?style=flat-square&labelColor=0d1117&logo=maildotru&logoColor=white" alt="Email" /></a>
<a href="https://www.linkedin.com/in/befikir/"><img src="https://img.shields.io/badge/linkedin-befikir-2dd4bf?style=flat-square&labelColor=0d1117&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yMC40NSAyMC40NWgtMy41NnYtNS41N2MwLTEuMzMtLjAyLTMuMDQtMS44NS0zLjA0LTEuODUgMC0yLjE0IDEuNDUtMi4xNCAyLjk0djUuNjdIOS4zNVY5aDMuNDF2MS41NmguMDVjLjQ4LS45IDEuNjQtMS44NSAzLjM3LTEuODUgMy42IDAgNC4yNyAyLjM3IDQuMjcgNS40NnY2LjI4ek01LjM0IDcuNDNhMi4wNiAyLjA2IDAgMSAxIDAtNC4xMyAyLjA2IDIuMDYgMCAwIDEgMCA0LjEzek03LjEyIDIwLjQ1SDMuNTZWOWgzLjU2djExLjQ1ek0yMi4yMiAwSDEuNzdDLjc5IDAgMCAuNzcgMCAxLjczdjIwLjU0QzAgMjMuMjMuNzkgMjQgMS43NyAyNGgyMC40NWMuOTggMCAxLjc4LS43NyAxLjc4LTEuNzNWMS43M0MyNCAuNzcgMjMuMiAwIDIyLjIyIDB6Ii8+PC9zdmc+" alt="LinkedIn" /></a>
<a href="https://globalcomputing.group"><img src="https://img.shields.io/badge/lab-GCLab_@_UTK-ff8200?style=flat-square&labelColor=0d1117&logo=academia&logoColor=white" alt="Global Computing Lab" /></a>

</div>

<br />

### `01` &nbsp;about

I'm a Ph.D. student in Computer Science (HPC concentration) at the **University of Tennessee, Knoxville**, where I'm a graduate research assistant in the [Global Computing Lab](https://globalcomputing.group) with Dr. Michela Taufer. I build **performance analysis tools for high-performance computing**. Most of my work asks one question: *why did this code run the way it did?*

- 🔬 &nbsp;**Now:** building an LLVM pass plugin that exposes compiler optimization remarks to annotation-based profilers such as [Caliper](https://github.com/LLNL/Caliper), so runtime performance can be traced back to compiler decisions.
- 🏛️ &nbsp;**Labs:** two summers at **Lawrence Livermore National Laboratory** (2024, 2025) and one at **Los Alamos National Laboratory** (2023).
- 🎓 &nbsp;**Recognition:** UTK Graduate Fellowship · ACM Student Research Competition at SC24 and SC25 · Lead Student Volunteer at SC25.
- 🐧 &nbsp;**Off the clock:** tinkering with NixOS and Hyprland, writing toy compilers, and slowly learning Rust.

<br />

### `02` &nbsp;where my cycles go

<img src="assets/flamegraph.svg" width="100%" alt="Flame graph of my time: hpc_performance_analysis (compiler_provenance, thicket, raja_perf_suite), reproducibility (anacin-x, dedup_ckpt), side_quests (compilers, nixos)" />

<sub>A not-very-scientific flame graph of my time. Wider bars mean more time.</sub>

<br />

### `03` &nbsp;research & open source

| project | what it does | my role |
| :-- | :-- | :-- |
| [**Thicket**](https://github.com/LLNL/thicket) | Python toolkit for exploratory analysis of *ensembles* of HPC performance profiles | developer · researcher |
| [**Hatchet**](https://github.com/LLNL/hatchet) | Analyzes calling-context trees from many HPC profilers through one common data model | developer · researcher |
| [**RAJAPerf**](https://github.com/LLNL/RAJAPerf) | RAJA Performance Suite. I use it to study performance portability across CPUs and GPUs | researcher |
| **Compiler provenance** | Records which compiler optimizations fired and links them to runtime data in Caliper and Thicket | developer · researcher |
| [**ANACIN-X**](https://github.com/TauferLab/ANACIN-X) | Trace-based analysis of non-deterministic behavior in MPI applications | developer · researcher |

<br />

### `04` &nbsp;publications & posters

> **RAJA Performance Suite: Performance Portability Analysis with Caliper and Thicket**<br />
> O. Pearce, J. Burmark, R. Hornung, **B. Bogale**, I. Lumsden, M. McKinsey, D. Yokelson, D. Boehme, S. Brink, M. Taufer, T. Scogland<br />
> `P3HPC @ SC'24` · <i>Workshop on Performance, Portability & Productivity in HPC</i>

> **Towards Affordable Reproducibility Using Scalable Capture and Comparison of Intermediate Multi-Run Results**<br />
> N. Tan, K. Assogba, W. J. Ashworth, **B. T. Bogale**, F. Cappello, M. M. Rafique, M. Taufer, B. Nicolae<br />
> `Middleware '24` · <i>25th ACM/IFIP International Middleware Conference</i>

<details>
<summary><b>posters</b>: ACM Student Research Competition</summary>
<br />

- **An Approach for Correlating Compiler Optimizations with Runtime Performance** · <sub>`ACM SRC @ SC'25`</sub>
- **Cluster-Based Methodology for Characterizing the Performance of Portable Applications** · <sub>`ACM SRC @ SC'24`</sub>

</details>

<br />

### `05` &nbsp;experience

| when | where | what |
| :-- | :-- | :-- |
| 2024&nbsp;→&nbsp;now | **UTK** · Graduate Research Assistant | LLVM pass plugin for compiler remarks; how compilers and `-O` levels shape application performance |
| summer&nbsp;2025 | **LLNL** · Defense Science & Technology Intern | Lightweight runtime provenance for compiler optimizations, integrated with Caliper and Thicket and validated on RAJAPerf |
| summer&nbsp;2024 | **LLNL** · Graduate Computing Scholar | Cluster-based method for characterizing portable application performance across CPU and GPU architectures |
| summer&nbsp;2023 | **LANL** · Parallel Computing Intern | Parallelized X-ray transport simulations with Kokkos, reaching a **>13× speedup** over serial |
| 2022&nbsp;→&nbsp;2024 | **UTK** · Undergraduate Research Assistant | Apptainer/Singularity containers for reproducibility, non-determinism in HPC, and dedup-based NN checkpointing |

<br />

### `06` &nbsp;toolbox

<p>
<img src="https://img.shields.io/badge/C++-0d1117?style=flat-square&logo=cplusplus&logoColor=00599C" alt="C++" />
<img src="https://img.shields.io/badge/C-0d1117?style=flat-square&logo=c&logoColor=A8B9CC" alt="C" />
<img src="https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=3776AB" alt="Python" />
<img src="https://img.shields.io/badge/Rust-0d1117?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
<img src="https://img.shields.io/badge/Shell-0d1117?style=flat-square&logo=gnubash&logoColor=4EAA25" alt="Shell" />
&emsp;
<img src="https://img.shields.io/badge/LLVM-0d1117?style=flat-square&logo=llvm&logoColor=white" alt="LLVM" />
<img src="https://img.shields.io/badge/Kokkos-0d1117?style=flat-square&logoColor=white" alt="Kokkos" />
<img src="https://img.shields.io/badge/RAJA-0d1117?style=flat-square" alt="RAJA" />
<img src="https://img.shields.io/badge/MPI-0d1117?style=flat-square" alt="MPI" />
&emsp;
<img src="https://img.shields.io/badge/pandas-0d1117?style=flat-square&logo=pandas&logoColor=white" alt="pandas" />
<img src="https://img.shields.io/badge/Jupyter-0d1117?style=flat-square&logo=jupyter&logoColor=F37626" alt="Jupyter" />
<img src="https://img.shields.io/badge/PyTorch-0d1117?style=flat-square&logo=pytorch&logoColor=EE4C2C" alt="PyTorch" />
&emsp;
<img src="https://img.shields.io/badge/Apptainer-0d1117?style=flat-square" alt="Apptainer" />
<img src="https://img.shields.io/badge/Docker-0d1117?style=flat-square&logo=docker&logoColor=2496ED" alt="Docker" />
<img src="https://img.shields.io/badge/NixOS-0d1117?style=flat-square&logo=nixos&logoColor=5277C3" alt="NixOS" />
<img src="https://img.shields.io/badge/Git-0d1117?style=flat-square&logo=git&logoColor=F05032" alt="Git" />
</p>

<br />

### `07` &nbsp;activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Yejashi/yejashi/output/snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Yejashi/yejashi/output/snake-light.svg" />
  <img src="https://raw.githubusercontent.com/Yejashi/yejashi/output/snake.svg" width="100%" alt="Snake eating my contribution graph" />
</picture>

<div align="center">
<sub>befikir@gclab:~$ <code>exit</code> &nbsp;·&nbsp; thanks for stopping by</sub>
</div>
