# Remaining Useful Life (RUL) Prediction via Local Linear Regression

An exploratory implementation of **Remaining Useful Life (RUL)** estimation for battery capacity degradation using non-parametric statistical learning and local polynomial smoothing.

---

## 📌 Project Overview

Predicting the Remaining Useful Life (RUL) of energy storage components is a core task in industrial condition monitoring and prognostics. This repository demonstrates capacity fade trend modeling using local linear regression to capture non-linear degradation trajectories without over-fitting.

## 🛠️ Key Methods & Features

- **Data Preprocessing**: Smoothing and filtering of battery charge/discharge telemetry.
- **Local Linear Regression**: Non-parametric estimation using localized linear bandwidth fitting.
- **Prognostic Extrapolation**: Projecting capacity fade trajectories to estimate RUL threshold crossing.

## 💻 Tech Stack

- **Language**: Python 3
- **Libraries**: `NumPy`, `pandas`, `scikit-learn`, `matplotlib`, `Jupyter Notebook`

## 📁 Repository Structure

- `RUL.ipynb` - Main analysis notebook detailing data loading, local regression fitting, and RUL visualization.
