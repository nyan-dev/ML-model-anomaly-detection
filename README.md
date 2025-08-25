# 🏥 Healthcare Data Anomaly Detection (Isolation Forest)

This project builds a **machine learning model** to detect unusual billing patterns in healthcare provider data.  
Using **Isolation Forest**, we automatically flag anomalies such as suspiciously high charges or abnormal service counts — providing insights that can assist auditors, healthcare analysts, and regulators.

Dataset: [Healthcare Providers Data (Kaggle)](https://www.kaggle.com/datasets/tamilsel/healthcare-providers-data)

---

## 🎯 Motivation & Goals
Manual review of millions of healthcare records is inefficient and often impossible.  
With anomaly detection, we can automatically highlight **suspicious billing behaviors** that deserve closer investigation.

This project demonstrates a **beginner-friendly workflow** including:
- Data cleaning & preprocessing  
- Feature selection (provider services & payment amounts)  
- Isolation Forest anomaly detection  
- Visualization of anomalies  
- Exporting results for further analysis  

---

## 🔍 Research Questions
1️⃣ Can we automatically detect anomalous billing patterns in healthcare provider data?  
2️⃣ Which providers exhibit unusual service or payment behavior compared to peers?  
3️⃣ How can anomaly detection methods like Isolation Forest assist healthcare auditors and analysts?  

---

## 🗂️ Project Structure
```

ML-model-anomaly-detection/
│
├── notebooks/
│   └── anomaly_detection.ipynb   # Main Colab/Jupyter workflow
│
├── data/
│   └── README.md                 # Instructions to download dataset
│
├── outputs/                      # Saved anomaly detection results & plots
│
├── requirements.txt              # Python dependencies
│
└── README.md                     # Project documentation

````

---

## ⚙️ Setup
Clone this repo and install dependencies:

```bash
git clone https://github.com/nyan-dev/ML-model-anomaly-detection.git
cd ML-model-anomaly-detection
pip install -r requirements.txt
````

Or simply open the notebook in **Google Colab** and upload the dataset.

---

## 🚀 Usage

1. Download dataset from Kaggle: [Healthcare Providers Data](https://www.kaggle.com/datasets/tamilsel/healthcare-providers-data)
2. Place the CSV into `/data/` (or upload directly in Colab).
3. Run the notebook step by step.
4. Results will be saved as `Healthcare_AnomalyResults.csv`.

---

## 📊 Results

* Anomalies flagged: \~5% of records (\~5,000 out of 100,000)
* Example visualizations:

  * Bar chart: Normal vs Anomalous providers
  * Scatter plot: Services vs Payment (highlighting anomalies)

📷 *(You can add screenshots of plots here once generated, e.g., `outputs/scatterplot.png`)*

---

## 📚 Tech Stack

* Python 3.x
* Pandas, NumPy
* Scikit-learn (Isolation Forest)
* Matplotlib, Seaborn

---

## 🧑‍💻 Author

**Nyan Lynn Htet**
MSc Data Science

🤖 AI Assistance: ChatGPT (Free Version)

