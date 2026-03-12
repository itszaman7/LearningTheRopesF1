# 🏎️ F1-ML-Lab: My AI & Data Science Journey

Welcome to my learning laboratory! This repository is a dedicated space where I apply **Machine Learning, Deep Learning, and NLP** techniques to the complex, data-rich world of Formula 1. 

As a passionate F1 fan, I use this domain to master data science concepts—moving from basic statistical analysis to complex predictive modeling. This project serves as a portfolio of my technical growth and problem-solving abilities for recruiters and collaborators.

---

## 🚀 The Learning Path

### 1. Fundamental ML & Data Engineering
*   **[Learning the Ropes](file:///e:/F1%20Learn%20ML/learningTheRopes/)**: Getting started with `FastF1`, handling API telemetry, and visualizing driver pace.
*   **[Intro to ML](file:///e:/F1%20Learn%20ML/introToML/)**: Exploring classification and regression.
    *   `qualiy_predict.ipynb`: Predicting qualifying positions based on historical season performance.
    *   `f1_ml.ipynb`: Core data cleaning and preprocessing workflows.

### 2. Deep Learning & Computer Vision (Planned)
*   *Upcoming*: Using CNNs to identify tire compounds from broadcast footage.
*   *Upcoming*: LSTM/RNN networks for real-time race strategy prediction.

---

## 🛠️ Technical Toolkit

- **Data Handling:** `Pandas`, `NumPy`, `FastF1` (API Integration)
- **Machine Learning:** `Scikit-Learn`, `XGBoost`
- **Visualization:** `Matplotlib`, `Seaborn`, `Plotly`
- **Environment:** `Jupyter`, `Python 3.x`, `Virtual Environments`

---

## 📊 Data Philosophy
To keep this repository lightweight and professional:
- **`archive/`** (Raw Data): All large CSV datasets (1950-Present) are kept locally and ignored by Git to ensure repository performance.
- **`f1_cache/`**: API telemetry cache is ignored to keep the codebase clean.
- **Reproducibility**: I include instructions on how to source the data from Kaggle or the Ergast API so my results are fully verifiable.

---

## 🏁 How to Run
1.  **Clone the Repo**: `git clone https://github.com/[your-username]/f1-learn-ml.git`
2.  **Setup Environment**: 
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows: .\env\Scripts\activate
    ```
3.  **Data**: Download the F1 dataset from Kaggle and place it in the `/archive` directory.

---

*“In Formula 1, data isn't just numbers; it's the difference between a podium and a DNF. This repo is where I learn to find that difference.”*
