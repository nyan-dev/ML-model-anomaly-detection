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
```
Or open directly in Google Colab and upload the dataset.

## 🚀 Usage

Download dataset from Kaggle: Healthcare Providers Data

Place the CSV into /data/ or upload in Colab

Run the notebook step by step

Results will be saved as Healthcare_AnomalyResults.csv

## 📊 Results

Anomalies flagged: ~5% of records (~5,000 out of 100,000)

Visualization:

Bar chart: Normal vs Anomalous providers

Scatter plot: Services vs Payment (highlighting anomalies)

## 🧑‍💻 Author
Nyan Lynn Htet
MSc Data Science

Ai Involved in this project
Chat GPT Free Version
