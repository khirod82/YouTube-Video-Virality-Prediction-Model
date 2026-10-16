# YouTube Video Virality Prediction Model

An end-to-end Machine Learning project that predicts whether a YouTube video will go **viral** based on pre-publication metadata (such as category, title length, description length, upload timing, and channel subscriber count). 

The project features a trained **Random Forest Classifier**, strict data leakage prevention, robust evaluation metrics, and an **interactive Jupyter widgets dashboard** for real-time inference.

---

## 📊 Project Overview & Features
* **Model Used:** Random Forest Classifier (`scikit-learn`)
* **Data Leakage Control:** Excluded post-publication metrics (`views`, `likes`, `comments`, `shares`) during training to ensure realistic, predictive performance.
* **Evaluation Metrics:** Achieved an **Accuracy of ~86%** and an **ROC-AUC Score of 0.89**.
* **Interactive Dashboard:** Built using `ipywidgets` allowing users to tune attributes (subscribers, duration, category, upload day/hour) and instantly test model predictions.

---

## Model Performance & Visualizations

### 1. Confusion Matrix
Evaluates model accuracy across viral and non-viral classes.
* *Accuracy:* `85.7%`

### 2. Receiver Operating Characteristic (ROC) Curve
* **AUC Score:** `0.89`

### 3. Top Feature Importances
The model identifies key drivers of virality, heavily weighted by channel subscriber count, video duration, description length, and title length.
---
