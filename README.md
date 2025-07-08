# 🩺 X-Ray Sentinel: AI-based Atelectasis Detection

## 🧩 Overview

**X-Ray Sentinel** is a machine learning-based system that detects **Atelectasis** in chest X-rays.  
Designed to assist radiologists, it delivers high-sensitivity predictions along with confidence-calibrated outputs and rich visual diagnostics.


## 🚀 Key Features

- 🎯 **Binary Classification:** 
  - Predicts **Atelectasis (Positive)** vs. **Normal (Negative)** cases.
- 📊 **Performance Dashboard:** 
  - Tracks **Accuracy**, **Sensitivity**, **Specificity**, and **AUC**.
- 🖼 **Visual Diagnostics:** 
  - ROC curve, confusion matrix, and confidence histograms.
- ⚙️ **Custom Thresholding:** 
  - Uses a 0.5 decision threshold for clinical interpretability.


## 🔬 Model Performance

| Metric         | Score  |
|----------------|--------|
| **Accuracy**   | 0.72   |
| **Sensitivity**| 0.94   |
| **Specificity**| 0.53   |
| **AUC (ROC)**  | 0.805  |

<sub>Test set evaluation summary</sub>

#### 🧾 Confusion Matrix

|                | Predicted Positive | Predicted Negative |
|----------------|--------------------|--------------------|
| **Actual Positive** | 34 (TP)            | 2 (FN)             |
| **Actual Negative** | 17 (FP)            | 19 (TN)            |


## 📈 Visual Insights

- **Confidence Score Histograms:**  
  Highlights how high-confidence positives cluster beyond the threshold.

- **ROC Curve:**  
  Demonstrates strong classification capacity with **AUC = 0.805**.


## ⚙️ Tech Stack

| Area              | Tools & Libraries             |
|-------------------|------------------------------|
| Programming       | Python                       |
| ML Frameworks     | Scikit-learn, XGBoost         |
| Visualization     | Matplotlib, Seaborn           |
| Image Processing  | OpenCV, PIL                   |


## 💡 Clinical Relevance

- Augments **radiologist workflows** for faster triage.
- Integrates seamlessly into **CDSS** (Clinical Decision Support Systems).
- Provides **transparent, confidence-driven predictions**.


## 🚀 Roadmap

✅ **Data Augmentation** — Improve generalization on varied datasets.  
✅ **Deep Learning** — Explore CNN models for spatial patterns.  
✅ **Dynamic Thresholding** — Tailor cutoffs based on patient risk.  
✅ **Web UI** — Interactive dashboards for healthcare teams.


## 📜 License

MIT License. Free to use & modify for research and clinical prototyping.


## 🤝 Contributions

Pull requests are welcome. If you find bugs or have feature requests, please open an issue.


## 📬 Contact

Built by **Sai Nikhil T**.  
For questions, email: tsainikhil1@gmail.com
