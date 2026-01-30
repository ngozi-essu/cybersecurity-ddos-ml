# cybersecurity-ddos-ml

Machine Learning–based DDoS Attack Detection using MLP and CNN | Cybersecurity, Network Traffic Classification, Deep Learning, Kaggle Dataset
# DDoS Attack Detection using Machine Learning
**Detecting malicious network traffic using the CICIDS2017 Dataset.**

## 📌 Project Overview
This project focuses on classifying network traffic as either 'Normal' or 'DDoS' (Distributed Denial of Service). Using the CICIDS2017 dataset, I implemented a machine learning pipeline to handle high-dimensional network data and identify attack patterns with high precision.

## 📊 The Data
- **Source:** [CICIDS2017 Dataset](https://www.unb.ca/cic/datasets/ids-2017.html)
- **Features:** 78 network flow features (Flow Duration, Packet Length, etc.)
- **Preprocessing:** Handled infinite values, performed feature scaling, and addressed class imbalance.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, Scikit-Learn, Matplotlib, Seaborn
- **Models Evaluated:** Random Forest, Decision Trees (or whichever you used)

## 📈 Key Results
- **Accuracy:** 99.x%
- **F1-Score:** 0.xx (Crucial for cybersecurity because false negatives are dangerous!)
- **Key Insight:** Features like `Bwd Packet Length Std` were top predictors for DDoS activity.

## 🚀 How to Run
1. Clone the repo: `git clone https://github.com/ngozi-essu/cybersecurity-ddos-ml.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the notebook: `jupyter notebook`
