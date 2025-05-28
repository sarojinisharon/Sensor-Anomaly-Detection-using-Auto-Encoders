# 📊 Sensor Anomaly Detection using Auto Encoders

This project explores unsupervised anomaly detection using autoencoders for sensor data. It simulates the detection of anomalies in unlabeled real-time sensor streams (torque, pressure, vibration) by analyzing reconstruction error from autoencoders. The detection logic was further improved by fine-tuning the anomaly threshold.

---

## 📌 Project Overview

- **Goal**: Detect anomalies in real-time sensor data using unsupervised learning.
- **Technique**: Autoencoder-based reconstruction error.
- **Outcome**: Improved anomaly recall by adjusting the threshold from the 95th to 90th percentile.

---

## 🧠 Key Concepts

- Unsupervised learning with Autoencoders  
- Reconstruction error as anomaly signal  
- Threshold tuning to balance recall and precision  
- Evaluation using precision, recall, and confusion matrix  
- Data visualization of anomaly points  

---

## 🛠️ Tech Stack

- Python  
- Jupyter Notebook  
- NumPy, Pandas  
- Matplotlib  
- Scikit-learn  

---

## 📈 Model Improvements

- Original model missed subtle anomalies (low recall).
- Threshold adjusted from **95th to 90th percentile** of reconstruction loss.
- Resulted in higher anomaly capture rate while maintaining acceptable precision.

---

## 💡 Learnings

- Fine-tuning thresholds is critical in unsupervised settings.
- Visual diagnostics help identify edge-case anomalies.
- Unlabeled sensor data needs creative evaluation strategies.

---

## 🚀 Future Scope

- Explore time-series LSTM autoencoders  
- Add PostgreSQL/SQLite sensor data integration  
- Build real-time dashboards for detected anomalies  
- Collaborate with domain experts to contextualize anomalies  

---

