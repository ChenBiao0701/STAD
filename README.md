# STAD: A Spatio-Temporal Self-Attention Framework for Effective Semantic-dependent Trajectory Anomaly Detection

This repository contains the source code for the paper:

> **STAD: A Spatio-Temporal Self-Attention Framework for Effective Semantic-dependent Trajectory Anomaly Detection**  

STAD is a novel framework designed to detect trajectory anomalies by leveraging spatio-temporal relationships and semantic dependencies through a self-attention mechanism. 

---

## Table of Contents
- [Installation](#installation)
- [Datasets](#datasets)  
- [Usage](#usage)  

---

## Installation

### Prerequisites
- Python >= 3.9  
- PyTorch >= 2.2.1  
- CUDA >= 12.1
- NumPy
- Scikit-Learn

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/chenbiao0701/STAD.git
   cd STAD
   ```
2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

---

## Datasets
The datasets used in our paper are collected by Kaggle and DiDi Chuxing:
1. [Porto](https://www.kaggle.com/c/pkdd-15-predict-taxi-service-trajectory-i/data)  
2. [Chengdu](https://outreach.didichuxing.com/research/opendata/en/)  

---

## Usage

### 1. Preprocess Data
Prepare your trajectory datasets according to the format described in the `data/README.md`. Use the provided scripts for preprocessing:
```bash
python preprocess.py
```

### 2. Train and Test the Model
Train and Test the STAD model on each datasets:
```bash
python main.py
```

---
