# Michael D. Stiber, Ph.D.

[![University](https://img.shields.io/badge/University%20of%20Washington-Bothell-4b2e83?style=flat-square&logo=academia&logoColor=white)](https://www.uwb.edu/stem/about/departments/css)
[![Lab](https://img.shields.io/badge/Research%20Lab-Intelligent%20Networks%20Laboratory-85754d?style=flat-square)](https://depts.washington.edu/biocomp/)
[![GitHub Org](https://img.shields.io/badge/GitHub%20Org-UWB--Biocomputing-181717?style=flat-square&logo=github)](https://github.com/UWB-Biocomputing)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-Citations-4285F4?style=flat-square&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=G4581GMAAAAJ)
[![ORCID](https://img.shields.io/badge/ORCID-0000--0002--1061--7667-A6CE39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0000-0002-1061-7667)
[![Faculty Page](https://img.shields.io/badge/Faculty%20Page-faculty.washington.edu%2Fstiber-005596?style=flat-square&logo=googlechrome&logoColor=white)](https://faculty.washington.edu/stiber/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/stiber)

Professor of Computing & Software Systems at the University of Washington Bothell and Principal Investigator of the [Intelligent Networks Laboratory](https://depts.washington.edu/biocomp/).

Research focuses on the intersection of complex networks, high-performance simulation, data and software provenance, and computational neuroscience.

---

## Research Focus

- **High-Performance Graph Simulation**: Construction of parallel simulation architectures capable of modeling tens of thousands of vertices and millions of edges across CPUs and GPUs.
- **Computational Neuroscience**: Investigation of developmental dynamics in cortical cultures, spatiotemporal burst propagation, avalanche statistics, and spike-timing-dependent plasticity (STDP).
- **Critical Infrastructure & Telecommunications**: Modeling and simulation of Emergency Services Communications Systems (ESCS / Next-Generation 911) for cybersecurity and resiliency assessment.
- **Scientific Workflow & Provenance Management**: Development of PROV-DM based systems to track relationships between models, code versions, execution parameters, and simulation datasets.

---

## Primary Open-Source Software

| Project | Description | Stack | Links |
| :--- | :--- | :--- | :--- |
| **[Graphitti](https://github.com/UWB-Biocomputing/Graphitti)** | High-performance graph-based systems simulator supporting internal vertex/edge states, dynamic topology changes, and message passing on CPUs and GPUs. | `C++` `CUDA` `CMake` | [![DOI](https://img.shields.io/badge/DOI-Zenodo-02428d?style=flat-square&logo=zenodo&logoColor=white)](https://zenodo.org/badge/latestdoi/273115663) [Repo](https://github.com/UWB-Biocomputing/Graphitti) |
| **[GraphSystemsAnalysis](https://github.com/UWB-Biocomputing/GraphSystemsAnalysis)** | Analytical pipelines for spatiotemporal point processes, avalanche identification, and network-wide bursting characterization. | `Python` `MATLAB` `C++` | [![DOI](https://img.shields.io/badge/DOI-Zenodo-02428d?style=flat-square&logo=zenodo&logoColor=white)](https://zenodo.org/badge/latestdoi/153203376) [Repo](https://github.com/UWB-Biocomputing/GraphSystemsAnalysis) |
| **[Mini-Torch](https://github.com/stiber/Mini-Torch)** | A Python framework designed for computer science students building neural networks from scratch; PyTorch with only `numpy`, `matplotlib`, and select elements of `scipy`. | `Python` | [Repo](https://github.com/stiber/Mini-Torch) |
| **[WorkBench](https://github.com/UWB-Biocomputing/WorkBench)** | Scientific workflow management platform centering on PROV-DM provenance visualization (`ProVis`) for reproducible simulations. | `Java` `Maven` `Swing` | [![DOI](https://img.shields.io/badge/DOI-Zenodo-02428d?style=flat-square&logo=zenodo&logoColor=white)](https://zenodo.org/badge/latestdoi/153203160) [Repo](https://github.com/UWB-Biocomputing/WorkBench) |
| **[BrainGrid](https://github.com/UWB-Biocomputing/BrainGrid)** | Parallel neural simulation engine for large-scale multi-cluster CPU/GPU simulation of cortical networks (predecessor to Graphitti). | `C++` `CUDA` `MPI` | [![DOI](https://img.shields.io/badge/DOI-Zenodo-02428d?style=flat-square&logo=zenodo&logoColor=white)](https://zenodo.org/badge/latestdoi/153202970) [Repo](https://github.com/UWB-Biocomputing/BrainGrid) |
| **[UML-Diagram-Generator](https://github.com/UWB-Biocomputing/UML-Diagram-Generator)** | Source-to-diagram utility generating Graphviz DOT UML class structures directly from C++ header and source files. | `Python` `Graphviz` | [Repo](https://github.com/UWB-Biocomputing/UML-Diagram-Generator) |
| **[Signal Computing](https://faculty.washington.edu/stiber/pubs/Signal-Computing/)** | Open-source textbook and computational curriculum: *Signal Computing: Digital Signals in the Software Domain*. | `LaTeX` `DSP` `Open Textbook` | [Book](https://faculty.washington.edu/stiber/pubs/Signal-Computing/) |

---

## Technical Domain & Stack

```
Languages:        C++, C, CUDA, Python, Java, MATLAB, SQL
High-Performance: OpenMP, MPI, POSIX Threads, GPU Computing (NVIDIA CUDA)
Systems & Tools:  CMake, Make, Git, Linux/UNIX HPC Environments, Graphviz, PROV-DM
Research Domains: Computational Neuroscience, Complex Network Science,
                  Emergency Services Communications (ESCS/NG911),
                  Digital Signal Processing, Scientific Data Provenance
```

---

## Selected Publications

- **Spatiotemporal Bursting in Simulated Cultures of Cortical Neurons** (2026)  
  M. Stiber, N. Gonzales, J.Y.H. Lee. *BioSystems*, 105868, [doi:10.1016/j.biosystems.2026.105868](https://doi.org/10.1016/j.biosystems.2026.105868).
- **Graph Neural Network Interpretation of Bursting in Biological Neuronal Networks** (2026)  
  H. Dhanasekaran, M. Stiber. *35th International Conference on Artificial Neural Networks (ICANN)*, Padua, Italy.
- **Effects of Spike Timing Dependent Plasticity on Structure and Behavior of Simulated Neural Networks** (2025)  
  V. Arndorfer, M. Stiber. *14th International Conference on Complex Networks and their Applications*, Binghamton, NY.
- **Graph-Based Simulation of Emergency Services Communications Systems** (2022)  
  J. Martinez Jordan, V. Salvatore, B. Endicott-Popovsky, V. Gandhi, C. O'Keefe, M.S. Sotebeer, M. Stiber. *Annual Modeling and Simulation Conference (ANNSIM)*.
- **Software and Data Provenance as a Basis for eScience Workflow** (2021)  
  J. Conquest, M. Stiber. *17th IEEE International Conference on eScience*.
- **Statistics of Inverse Interspike Intervals: The Instantaneous Firing Rate Revisited** (2018)  
  L. Kostal, P. Lansky, M. Stiber. *Chaos*, 28(10), 106305.
- **BrainGrid + Workbench: High-Performance/High-Quality Neural Simulation** (2017)  
  M. Stiber, F. Kawasaki, D. Davis, H.U. Asuncion, J.Y.H. Chu, D. Boyer. *International Joint Conference on Neural Networks (IJCNN)*.
- **Bringing High Performance Neural Simulation to the Desktop with BrainGrid** (2016)  
  M. Stiber, F. Kawasaki, M. Strange, A. Watson. *International Workshop on Neuronal Coding*.
- **A Simple Model of Cortical Culture Growth: Burst Property Dependence on Network Composition and Activity** (2014)  
  F. Kawasaki, M. Stiber. *Biological Cybernetics*, 108(4), 423–443.

Full publication list available via [Google Scholar](https://scholar.google.com/citations?user=G4581GMAAAAJ), [ORCID](https://orcid.org/0000-0002-1061-7667), and the [INL Publications Archive](https://depts.washington.edu/biocomp/publications.html).

---

## Academic Background & Appointments

- **Professor**, Computing & Software Systems, University of Washington Bothell (1997–present; Founding Faculty)
- **Chair**, Computing & Software Systems Division, UW Bothell (2023–2025)
- **Director of Cybersecurity Initiatives**, UW Bothell (2022–2023)
- **Associate Dean**, School of STEM, University of Washington Bothell (2013–2019)
- **Fulbright Scholar**, Institute of Physiology, Czech Academy of Sciences
- **Assistant Professor**, Hong Kong University of Science & Technology (HKUST)
- **Research Assistant Professor**, University of California, Berkeley
- **Ph.D. in Computer Science**, University of California, Los Angeles (UCLA), 1992
- **M.S. in Computer Science**, University of California, Los Angeles (UCLA), 1990
- **B.S. in Computer Science & Electrical Engineering**, Washington University in St. Louis

---

## Contact & Links

- **Institutional Webpage**: [faculty.washington.edu/stiber](https://faculty.washington.edu/stiber/)
- **Laboratory Webpage**: [depts.washington.edu/biocomp](https://depts.washington.edu/biocomp/)
- **Organization GitHub**: [github.com/UWB-Biocomputing](https://github.com/UWB-Biocomputing)
- **Google Scholar**: [Michael Stiber](https://scholar.google.com/citations?user=G4581GMAAAAJ)
- **ORCID**: [0000-0002-1061-7667](https://orcid.org/0000-0002-1061-7667)
- **LinkedIn**: [linkedin.com/in/stiber](https://www.linkedin.com/in/stiber)

---

<sub>*This work has been partially generated with use of a language model (AI), and the author has read through and tested the resulting content to ensure it accurately reflects the original intent. All errors are the responsibility of the author.*</sub>

