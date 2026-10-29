# SA-DCM: Self-Adaptive Differentiable Clustering Method for Hyperspectral Image Classification Network Compression

This repository contains the implementation and experimental notebooks for **SA-DCM (Self-Adaptive Differentiable Clustering Method)**, a model compression method for hyperspectral image classification networks.

SA-DCM is applied to different base architectures and evaluated on multiple benchmark hyperspectral image datasets to study network compression while maintaining classification performance.

## Base Architectures

The SA-DCM method is evaluated on the following base architectures:

- **SST** – Spectral–Spatial Transformer
- **HybridSN** – Hybrid Spectral Network
- **SpectralGPT** – Spectral foundation model architecture
- **GCN** – Graph Convolutional Network

## Datasets

The experiments use the following hyperspectral image datasets:

- **Indian Pines (I)** – Hyperspectral agricultural dataset.
- **Pavia University (PU)** – Urban hyperspectral image dataset.
- **Pavia (P)** – Pavia hyperspectral dataset used in the experiments.
- **Botswana (B)** – Hyperspectral dataset acquired over the Okavango Delta region.
- **Salinas (S)** – Agricultural hyperspectral dataset.
- **Oil Spill (O)** – Oil-spill hyperspectral dataset used in the experiments.

## Experimental Notebooks

The notebooks are organized according to the combination of dataset and base architecture on which SA-DCM is applied.

| Notebook | Dataset(s) | Base architecture |
|---|---|---|
| `B, I, S - SpectralGPT.ipynb` | Botswana, Indian Pines, Salinas | SpectralGPT |
| `B, PU - HybridSN.ipynb` | Botswana, Pavia University | HybridSN |
| `GCN.ipynb` | All datasets | Graph Convolutional Network |
| `I,O,S - HybridSN.ipynb` | Indian Pines, Mesanas Oil Spill, Salinas | HybridSN |
| `P - HybridSN.ipynb` | Pavia | HybridSN |
| `P, PU - SpectralGPT.ipynb` | Pavia, Pavia University | SpectralGPT |
| `SST.ipynb` | All datasets | Spectral–Spatial Transformer |

**Note:** Dataset and architecture mappings should be interpreted according to the actual experimental configurations in each notebook.

## Research Publication

The work associated with this repository is published in *IEEE Geoscience and Remote Sensing Letters*.

**Citation:**

N. K. Nadipelli, T. Hitendra Sarma, R. Dharma Reddy, and A. Radoi, “SA-DCM: Self-Adaptive Differentiable Clustering Method for Compression of Hyperspectral Image Classification Networks,” *IEEE Geoscience and Remote Sensing Letters*, doi: [10.1109/LGRS.2026.3744953](https://doi.org/10.1109/LGRS.2026.3744953).

## Keywords

Hyperspectral imaging; model compression; differentiable clustering; HybridSN; Spectral–Spatial Transformer; Graph Convolutional Network; network optimization; quantization.

## Acknowledgment

Please cite the above publication when using this work in research or when building upon the SA-DCM methodology.
