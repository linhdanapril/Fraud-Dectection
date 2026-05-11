# 🔍 Fraud Detection Using Incremental DBSCAN

> An unsupervised anomaly detection approach that leverages Incremental DBSCAN to identify fraudulent transactions in a simulated streaming environment.

---

## 📌 Overview

Traditional clustering algorithms process data in batch mode, making them impractical for real-world fraud detection where data arrives continuously. This project explores **Incremental DBSCAN (IDBSCAN)** as a scalable alternative, capable of updating clusters as new data points arrive — without reprocessing the entire dataset.

---

## 🛠️ Technologies

- **Language:** Python
- **Clustering:** IDBSCAN, Scikit-learn (KMeans, HAC, DBSCAN)
- **Visualization:** Matplotlib, Seaborn

---

## 📁 Project Structure

---

## ⚙️ Methodology

1. **Parameter Selection** — Tuned `eps` and `min_samples` using the Elbow Method
2. **Incremental Learning** — Trained on an initial batch, then updated with incremental data to simulate streaming
3. **Evaluation** — Assessed using Silhouette Score, ARI, runtime, and memory usage
4. **Benchmarking** — Compared against KMeans, HAC, and DBSCAN; IDBSCAN achieved the highest clustering stability
