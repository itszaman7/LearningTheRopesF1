# 🏎️ F1-ML-Lab: My AI & Data Science Journey

Welcome to my learning laboratory! This repository is a dedicated space where I apply **Machine Learning, Deep Learning, and NLP** techniques to the complex, data-rich world of Formula 1. 

As a passionate F1 fan, I use this domain to master data science concepts—moving from basic statistical analysis to complex predictive modeling. This project serves as a portfolio of my technical growth and problem-solving abilities for recruiters and collaborators.

---

## 🚀 The Learning Path

### 1. Fundamental ML & Data Engineering
*   **[Learning the Ropes](file:///e:/F1%20Learn%20ML/learningTheRopes/)**: API integration with `FastF1` for telemetry and pace visualization.
*   **[Intro to ML](file:///e:/F1%20Learn%20ML/introToML/)**: Building predictive models with `Scikit-Learn`:
    *   `regression.ipynb`: Predicting continuous lap times using tire life and track history.
    *   `qualiy_predict.ipynb`: Multi-class classification (Q1/Q2/Q3) using **Random Forest** and **One-Hot Encoding**.
    *   `f1_ml.ipynb`: Solving **data imbalance** in race winning predictions with **Logistic Regression**.
*   **Core Skills**: Mastered **feature engineering** (Driver Form, Track Experience) and complex data joins with **Pandas/NumPy**.

### 2. Deep Learning & Computer Vision (Planned)
*   *Upcoming*: Using CNNs to identify tire compounds from broadcast footage.
*   *Upcoming*: LSTM/RNN networks for real-time race strategy prediction.

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
