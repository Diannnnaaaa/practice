# 🏥 OCT Image Classification
**Optical Coherence Tomography Image Classification for Retinal Disease Diagnosis**

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![PyTorch](https://img.shields.io/badge/PyTorch-1.9+-ee4c2c.svg)](https://pytorch.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📋 Table of Contents
- [Overview](#-overview)
- [Dataset](#-dataset)
- [Methodology](#-methodology)
- [Results](#-results)
- [Acknowledgments](#-acknowledgments)

## 🎯 Overview
This project is a deep learning solution for OCT image classification, developed as part of a research-oriented learning task. The goal is to classify retinal images into **CNV, DME, DRUSEN, and NORMAL** categories.

## 📊 Dataset
The dataset includes retinal OCT images divided into:
* CNV (0)
* DME (1)
* DRUSEN (2)
* NORMAL (3)

## ⚙️ Methodology
### Data Augmentation
...
### Handling Class Imbalance
...
### Training Strategy
...

## Results
| Metric | Value |
|--------|-------|
| **Best Validation Accuracy** | **96.17%** |
| **Best Validation Loss** | **0.0379** |
| **Best Training Accuracy** | 76.82% |
| **Training Time** | 1h 32m 22s |

## Training Log Summary
| Epoch | Val Acc | Val Loss |
|-------|---------|----------|
| 1 | 0.9291 | 0.0733 |
| ... | ... | ... |
| 4 | **0.9617** | **0.0379** |
| ... | ... | ... |