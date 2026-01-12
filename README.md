# 📈 Quantum-Driven Hybrid Deep Learning Model for Forex Price Prediction (QuForex)

This repository contains a **Quantum–Classical Hybrid Deep Learning model** for **Forex price prediction**, implemented entirely in a **single Jupyter Notebook**.

The project explores how **Variational Quantum Circuits (VQCs)** can be integrated with classical deep learning models such as **LSTM, GRU, and Transformer** to improve forecasting accuracy and stability in highly non-linear and chaotic Forex markets.

This work is part of the **QuForex** project developed under the **Quantum Computing** track in the Department of Computer Science and Engineering.

---

## 📘 Project Overview

Forex markets exhibit strong non-stationarity, regime shifts, and complex dependencies that challenge traditional statistical and deep learning models.

This project proposes a **hybrid quantum–deep learning framework** where:
- Classical deep models handle temporal dependencies
- Quantum circuits provide expressive, high-dimensional feature representations
- Training is performed end-to-end using hybrid quantum–classical optimization

The complete implementation, experiments, and visualizations are contained in **one notebook** for clarity and reproducibility.

---

## 🧠 Key Features

- Hybrid **Quantum–Classical** learning pipeline
- Support for:
  - LSTM
  - GRU
  - Transformer
  - Quantum-enhanced variants (QLSTM, QGRU, QTransformer)
- Variational Quantum Circuits (VQC) as trainable layers
- Multi-seed evaluation for robustness
- Comparison with classical baselines

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Scikit-learn
- PyTorch
- PennyLane (quantum simulation)
- Matplotlib

---

## 📂 Repository Structure

```text
.
├── Quforex_PROJECT.ipynb
└── README.md
