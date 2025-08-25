# 🏥 Healthcare Data Anomaly Detection (Isolation Forest)

This project applies **machine learning anomaly detection** on a large healthcare provider dataset 
([Kaggle link](https://www.kaggle.com/datasets/tamilsel/healthcare-providers-data)) 
using **Isolation Forest**.

## 📌 Project Intention
Manual review of millions of healthcare records is not practical. 
We use anomaly detection to automatically flag unusual provider billing patterns 
(e.g., suspiciously high charges, abnormal service counts).

This project is beginner-friendly and demonstrates:
- Data cleaning & preprocessing
- Feature selection (provider services & payment amounts)
- Isolation Forest anomaly detection
- Visualization of anomalies
- Saving results for further analysis

## 🔍 Research Questions
1. Can we automatically detect anomalous billing patterns in healthcare provider data?
2. Which providers exhibit unusual service or payment behavior compared to peers?
3. How can anomaly detection methods like Isolation Forest help auditors or healthcare analysts?

## 🗂️ Project Structure
- `notebooks/anomaly_detection.ipynb` → Colab notebook with full workflow (with Burmese + English explanations)
- `data/README.md` → instructions to download dataset
- `outputs/` → saved anomaly detection results
- `requirements.txt` → Python dependencies

## ⚙️ Setup
Clone this repo and install dependencies:

```bash
git clone https://github.com/<your-username>/healthcare-anomaly-detection.git
cd healthcare-anomaly-detection
pip install -r requirements.txt
