# ⚛️ EqV2-SingleAtomOER

![Python](https://img.shields.io/badge/python-3.10+-blue.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Dataset](https://img.shields.io/badge/Dataset-CC%20BY%204.0-orange.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)

**Fine-tuning of the pretrained EquiformerV2 graph neural network for adsorption-energy and force prediction on single-atom-incorporated oxyhydroxide catalysts.**

---

## 🧩 Overview
This repository provides the source code, processed dataset, and pretrained checkpoints used for the fine-tuning and evaluation of **EquiformerV2**, adapted for **M₁–NiFeOOH-type single-atom-incorporated oxyhydroxide catalysts**.  
The fine-tuned model enables accurate prediction of adsorption energies and interatomic forces for complex transition-metal oxyhydroxide systems.

---

## 📂 Directory Structure

- `configs/` – Training and evaluation configurations  
- `checkpoints/` – Pretrained and fine-tuned model weights  
- `data/` – Processed dataset and split information  
- `scripts/` – Model, dataset, and training scripts  
- `results/` – Example output figures

---

## 🚀 Usage
Executable Jupyter notebooks demonstrating model training, validation, and inference  
will be added in a future update.

The current version includes:
- Configuration files for training and fine-tuning  
- DFT-relaxed datasets and split indices  
- Pretrained and fine-tuned checkpoints for reproducibility  

---

## 🔗 Checkpoints
Pretrained and fine-tuned model weights can be downloaded from Google Drive:

📁 [**Download from Google Drive**](https://drive.google.com/file/d/1CWOApeaC5s7q-Ex2h1b2UC-Kt6E73x5q/view?usp=drive_link)

| File | Description |
|------|--------------|
| `baseline_eqv2.pt` | Pretrained EquiformerV2 model (OC22 baseline) |
| `finetuned_eqv2_singleatom.pt` | Fine-tuned model on custom DFT dataset (M₁–NiFeOOH systems) |

---

## 🪪 License
- **Code:** MIT License  
- **Dataset:** CC BY 4.0 License  
MIT License
Copyright (c) 2025 Jaehyun Kim

---
