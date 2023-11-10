# Reproducible Analysis and Statistics
We aim to develop an analysis framework to facilitate reproducible and flexible neuroimaging analyses and allow the assessment and optimisation of the reproducibility of such analyses.

## Principles
We focus on three main principles to support reproducible analyses.

### Reproducibility
- Explicit specification of dependency between steps
- Clear recording and visualisation of provenance
- Tight control of loading/unloading tools
- High- and low-level data diagnostics
- Data integrity (checksum) recorded and checked at every step

### Inclusivity
- Compatible with both MATLAB and OCTAVE
- Tested on both Windows and Linux (Ubuntu)
- Integration of a large variety of MATLAB/OCTAVE-, Linux- and Python-based neuroimaging tools

### Efficiency
- Parallel execution on a single workstation and an HPC
- Modular design
- Core + extensions architecture
- Interface to download data from common sources, including OpenNEURO
- Installation scripts for tools
