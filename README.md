# G-DDPM: Graph-based Denoising Diffusion Probabilistic Model

**Probabilistic Forecasting of Renewable Energy and Electricity Demand**

![License](https://img.shields.io/badge/license-CC%20BY--4.0-brightgreen)
![Python](https://img.shields.io/badge/python-3.8%2B-blue)
![Model](https://img.shields.io/badge/model-Diffusion%20%2B%20Graph--Neural--Network-purple)

This repository contains the official implementation of the paper:

**[Probabilistic Forecasting of Renewable Energy and Electricity Demand using Graph-based Denoising Diffusion Probabilistic Model (G-DDPM)](https://doi.org/10.1016/j.egyai.2024.100459)**  
Amir Miraki, Pekka Parviainen, Reza Arghandeh  
Published in *Energy and AI*, Volume 19, 2025

## 🌟 Highlights

- 🔄 **Diffusion-based probabilistic forecasting** for multivariate time series
- 🌐 **Graph-based modeling** of variable interdependencies
- ⏱️ **Parallel feature extraction** for both spatial and temporal information
- 📊 **State-of-the-art performance** on real-world energy datasets
- 🧠 Incorporates **GRU, Gated Graph Convolutions, and Dilated Convolutions**
- 📉 Outperforms DeepAR, TimeGrad, GCRDD, SpecSTG, and others on MAE, RMSE, CRPS

## 📖 Paper Abstract

The paper introduces G-DDPM, a novel diffusion-based generative model that combines temporal modeling with graph-based representations to capture dependencies between variables in multivariate time series. Tested on two real-world datasets (renewable energy and electricity demand), G-DDPM significantly outperforms existing forecasting models in terms of accuracy and uncertainty quantification.

> 🔗 Full paper: [ScienceDirect](https://doi.org/10.1016/j.egyai.2024.100459)

## 📁 Datasets

This repo uses two public datasets:
1. **Renewable Energy**: CAISO & NREL data (solar, wind, weather, demand)
2. **Electricity Demand**: Hourly load of 370 clients from a public benchmark

## 📈 Performance Summary

| Method       | MAE ↓     | RMSE ↓    | CRPS ↓    |
|--------------|-----------|-----------|-----------|
| DeepAR       | High      | High      | High      |
| SpecSTG      | Medium    | Medium    | Medium    |
| TimeGrad     | Good      | Good      | Good      |
| **G-DDPM**   | **Best**  | **Best**  | **Best**  |

## 🚀 Getting Started

### Requirements

- Python 3.8+
- PyTorch
- NumPy
- NetworkX
- tqdm

### Installation

```bash
git clone https://github.com/AmirMiraki/GDDPM.git
cd GDDPM


