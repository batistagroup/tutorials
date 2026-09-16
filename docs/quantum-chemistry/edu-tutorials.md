# Educational Tutorials

A comprehensive collection of quantum chemistry and computational chemistry tutorials from the Batista Group, covering various computational methods, molecular simulations, and software tools.

## Molecular Simulation and Dynamics

### Interfacial Electron Transfer
- **[Hands on Simulations of Interfacial Electron Transfer](https://files.batistalab.com/teaching/tutorials/iet_pchem_version2.pdf)** - Practical guide to simulating electron transfer at interfaces
- **[Aligning Fermi Levels](https://files.batistalab.com/teaching/tutorials/iet_EF.pdf)** - Supplementary tutorial on Fermi level alignment for interfacial systems

### Quantum Dynamics
- **[Quantum Dynamics](https://files.batistalab.com/teaching/tutorials/QuantumDynamics.pdf)** - Introduction to quantum dynamical simulations
- **[Time-Sliced Thawed Gaussian Propagation for Simulations of Quantum Dynamics](http://www.birs.ca/events/2016/5-day-workshops/16w5006/videos/watch/201601281933-Batista.html)** - Video lecture on advanced quantum dynamics methods
- **[Hierarchical Equations of Motion (HEOM)](https://files.batistalab.com/teaching/tutorials/HEOM_tutorial.pdf)** - Derivation and Python implementation of open-system quantum dynamics, including convergence tests and QUAPI/TEMPO comparisons

    - [![Open in Colab][colab-badge]][heom-notebook] [QUAPI convergence and HEOM comparison][heom-notebook]

- **[Feynman–Vernon Influence Functional: QUAPI, TEMPO, and Process Tensors](https://files.batistalab.com/teaching/tutorials/QUAPI_Process_Tensor_tutorial.pdf)** - Step-by-step time-sliced derivation, finite-memory QUAPI and persistent-MPS implementations, and reusable process tensors for multitime spectroscopy

    - [![Open in Colab][colab-badge]][quapi-notebook] [Ohmic qubit: dense QUAPI and persistent-MPS propagation][quapi-notebook]
    - [![Open in Colab][colab-badge]][process-tensor-notebook] [Process-tensor spectroscopy: pulses and multitime signals][process-tensor-notebook]
  
## Computational Methods and Theory

### Quantum Eigenstate Calculations

- **[Collocation Methods for Computing Quantum Eigenstates](https://files.batistalab.com/teaching/tutorials/Collocation_tutorial.pdf)** - Square and rectangular collocation with Gaussian-basis Morse-oscillator examples and point-selection strategies

    - [![Open in Colab][colab-badge]][collocation-notebook] [2D Morse collocation: beam search versus pivoted QR][collocation-notebook]

### Tensor-Network Methods

- **[DMRG for Quantum Eigenstates](https://files.batistalab.com/teaching/tutorials/DMRG_tutorial.pdf)** - Density-matrix renormalization group for vibrational eigenstates using binary tensorization, matrix-product states, TT-cross, and matrix-free Hamiltonians

    - [![Open in Colab][colab-badge]][dmrg-notebook] [Morse eigenstates with DMRG and TT-cross][dmrg-notebook]

- **[Quantics Tensor Trains (QTT) for Vibrational Eigenstates](https://files.batistalab.com/teaching/tutorials/QTT_tutorial.pdf)** - Imaginary-time propagation with physical-core Fourier transforms and block Rayleigh–Ritz calculations in compressed tensor-train form

    - [![Open in Colab][colab-badge]][qtt-notebook] [QTT eigenstates by imaginary-time propagation][qtt-notebook]

### Redox Chemistry
- **[Tutorial on Ab Initio Redox Potential Calculations](https://files.batistalab.com/teaching/tutorials/redoxpotentials.pdf)** - Guide for calculating redox potentials from first principles

### Molecular Design
- **[Inverse Molecular Design](http://192.132.64.115/imdDocument/index.html)** - Tool and tutorial for inverse molecular design approaches

### QM/MM Methods
- **[Mod-QM/MM method](http://gascon.chem.uconn.edu/software)** - Information on modified QM/MM methodology


## Software-Specific Tutorials

### DFTB Methods
- **[DFTB with DFTB+ or Gaussian](https://files.batistalab.com/teaching/tutorials/dftb/DFTB_forBatistaLab_Jan3_2017_withG09.pdf)** - Density functional tight-binding tutorial
  - **Resources:**
    - [DFTBscriptfiles_noexecutable.zip](https://files.batistalab.com/teaching/tutorials/dftb/DFTBscriptfiles_noexecutable.zip)
    - [alanine_dftb_lufeng.com](https://files.batistalab.com/teaching/tutorials/dftb/alanine_dftb_lufeng.com)

### Gaussian 09
- **[Quick Tutorial on Natural Bond Order 3 Calculations Within Gaussian 09](https://files.batistalab.com/teaching/tutorials/nbo/Tutorial_NBO.pdf)** - NBO analysis in Gaussian
  - **Resources:**
    - [allBonds.gjf](https://files.batistalab.com/teaching/tutorials/nbo/allBonds.gjf)

- **[Advice on Effective Core Potential (ECP) Basis Sets](https://files.batistalab.com/teaching/tutorials/gaussian/ECP_bases.pdf)** - Guide for selecting appropriate ECP basis sets

### EXAFS Spectroscopy
- **[Tutorial on Simulating EXAFS Using Demeter](https://files.batistalab.com/teaching/tutorials/exafs/tutorialEXAFS_Oct2016.pdf)** - Extended X-ray absorption fine structure simulations
  - **Resources:**
    - [Build_EXAFS_Oct2016.tar.gz](https://files.batistalab.com/teaching/tutorials/exafs/Build_EXAFS_Oct2016.tar.gz)

### Transport and Advanced Methods
- **[Non-equilibrium Green's Function Calculations with TranSIESTA](https://files.batistalab.com/teaching/tutorials/NEGF_TranSIESTA/TranSIESTA_tutorial1.3.pdf)** - Electronic transport calculations
  - **Resources:**
    - [Benzenedithiol.mol2](https://files.batistalab.com/teaching/tutorials/NEGF_TranSIESTA/Benzenedithiol.mol2)
    - [Au67.mol2](https://files.batistalab.com/teaching/tutorials/NEGF_TranSIESTA/Au67.mol2)
    - [Utils.zip](https://files.batistalab.com/teaching/tutorials/NEGF_TranSIESTA/Utils.zip)

### Electron Transfer Theory
- **[Marcus Theory with Gaussian and ADF](https://files.batistalab.com/teaching/tutorials/Marcus/MarcusTheory_tutorial_5.pdf)** - Classical electron transfer theory calculations
  - **Resources:**
    - [MarcusFiles.zip](https://files.batistalab.com/teaching/tutorials/Marcus/MarcusFiles.zip)

[colab-badge]: https://colab.research.google.com/assets/colab-badge.svg

<!-- QUAPI_HEOM_convergence.ipynb -->
[heom-notebook]: https://colab.research.google.com/drive/1bWLMC9R2zMUI6pYFnVFP7U3WD22R3ySt

<!-- Qubit_Ohmic_Persistent.ipynb -->
[quapi-notebook]: https://colab.research.google.com/drive/19p-_qFC4OjpUlaq78qo2qqiM9M20kIzi

<!-- process_tensor_spectroscopy.ipynb -->
[process-tensor-notebook]: https://colab.research.google.com/drive/1svH6LS9yR--YyvzUUVOF2hLpH7jLFM2X

<!-- Collocation_beam_search.ipynb -->
[collocation-notebook]: https://colab.research.google.com/drive/173iA9mFAxOQ92-M7zKuHy4xju9uny92S

<!-- DMRG_Morse_TTcross.ipynb -->
[dmrg-notebook]: https://colab.research.google.com/drive/1Nzq_RK8HU6IOcQhavh_uwcLr1La6LhIh

<!-- QTT_tutorial.ipynb -->
[qtt-notebook]: https://colab.research.google.com/drive/10ETRRBT5-rzgnrO5II9RbqFWJ1EcK_Hu