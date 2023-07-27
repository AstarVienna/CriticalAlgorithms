# Critical Algorithms
METIS FDR delivery E-LIS-AST-MET-1012: "Software Modules, Simulated Data and Documentation Package"

## Setup

First install git-lfs, then clone the repository.

### Git lfs
This repository uses git-lfs and git-submodules.
It is therefore necessary to install git-lfs.
This has to be done only once, and might already be done for your setup.

First install git-lfs, which depends on your specific system.
For example on Ubuntu do
```
sudo apt-get install git-lfs
```

Then initialize git-lfs:
```
git lfs install
```

### Cloning the repository

The repository can be cloned once git-lfs is installed and initialized: 

```
git clone --recurse-submodules https://github.com/AstarVienna/CriticalAlgorithms.git
```

## Critical Algorithms

This repository contains prototypes for four critical algorithms as described
in the METIS Data Reduction Library Design (E-REP-AST-MET-1006 v1-0).

### 5a. LSS Wavelength calibration and distortion correction

See `5a-LSS-wavelength-calibration-PyReduce-ELT` directory.

### 5b. IFU Wavelength calibration and distortion correction

See `5b-IFU-distortion` directory.

### 9. IFU image and cube reconstruction

See `9-IFU-image-reconstruction` directory.

### 11. ADI algorithm

See `11-ADI-algorithm` directory.

