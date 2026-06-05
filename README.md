# SingleWaveReconstructionData

Datasets supporting the paper:

> F. Wang, "Single-Waveform Time-Series Modeling via Kernel-Based Dynamic Mode 
> Decomposition for Real-Time Dynamics Reconstruction," 
> *Phys. Rev. Accel. Beams* (2026). DOI: [10.1103/vbnq-lj9j](https://doi.org/10.1103/vbnq-lj9j)

## Datasets

Two datasets from pulsed accelerator subsystems at **SSRL, SLAC National Accelerator Laboratory**:

- **`ickerWF.zip`** — Current waveforms from three SSRL beam kicker systems 
  (booster extraction, booster injection, SPEAR3 injection), sampled at 100 MHz, 
  spanning 2021–2024 (~3 years, several hundred waveforms per system).

- **`LinK2_K3_raw.zip`** — Raw current and voltage waveforms from two PFN 
  modulator systems (K2 and K3) on the SSRL Linac, sampled at 100 MHz.

## Usage

Data is in MATLAB `.mat` format. Load with:
```matlab
data = load('LinK2_K3_raw.mat');   % MATLAB

Acknowledgment
Supported by the U.S. Department of Energy under Contract No. DE-AC02-76SF00515.
