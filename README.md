<h1 align="center">🧠 Consumer Complaint Analysis using NLP & Machine Learning</h1>

<p align="center">
  <b>End-to-end text analytics project leveraging NLP & ML to uncover consumer sentiment, fraud patterns, and complaint trends from CFPB data.</b><br>
  <i>📅 2019–2024 | 🧮 Python · NLP · Machine Learning · Pandas · NLTK · Scikit-learn · Seaborn</i>
</p>

---

## 🎯 Project Overview
This project analyzes the **U.S. Consumer Financial Protection Bureau (CFPB)** complaint dataset using **Natural Language Processing (NLP)** and **Machine Learning**.  
It identifies hidden insights from consumer narratives — such as sentiment polarity, emerging complaint clusters, and potential fraud indicators.

---

## 📊 Dataset
**Source:** [CFPB Consumer Complaint Database](https://www.consumerfinance.gov/data-research/consumer-complaints/)  
Contains millions of authentic U.S. consumer complaints across various financial products (credit cards, loans, reporting agencies, etc.).

---

## 🧩 Methodology

### 🧹 Data Preparation
- Cleaned and standardized complaint text.  
- Converted date columns into datetime format.  
- Sampled 20K rows for efficient NLP processing.

### 📈 Exploratory Data Analysis
- Identified top companies and states by complaint volume.  
- Analyzed trends, response times, and disputed cases.

### 💬 Sentiment Analysis (VADER)
- Applied **NLTK’s VADER** to classify text into **Positive / Negative / Neutral**.  
- Visualized sentiment distribution to measure consumer tone.

### 🧠 Topic Modeling (LDA)
- Used **Gensim’s LDA** for topic extraction.  
- Revealed themes like **credit report errors**, **debt collection**, **unauthorized charges**, etc.

### 🔍 Fraud Detection (ML)
- Tagged fraud-related complaints via keyword heuristics.  
- Applied **TF-IDF vectorization** and trained a **Random Forest Classifier**.  
- Achieved **98% Accuracy** and **ROC-AUC = 0.995**.

---

## 💡 Key Insights
| Metric | Insight |
|:--|:--|
| 🏦 **Top Fraud Companies** | Experian, Equifax, TransUnion, PayPal, Chase |
| 📍 **Hotspot States** | California, Florida, Texas, New York |
| ⏱️ **Response Rate** | 98.76% of companies responded within time |
| 😠 **Sentiment** | 60%+ of complaints are negative |

---

## 📈 Visual Insights

<div align="center">

### 🎭 Sentiment Distribution
<img width="85%" alt="Sentiment Distribution" src="https://raw.githubusercontent.com/dipondasrahul-blip/Consumer-Complaint-Analysis-NLP-ML/main/Sentiment%20Distribution%20Chart.jpg" />

---

### 🧩 Complaint Topic Clusters (LDA)
<img width="85%" alt="Complaint Topic Clusters" src="https://raw.githubusercontent.com/dipondasrahul-blip/Consumer-Complaint-Analysis-NLP-ML/main/Complaint%20Topic%20Clusters.jpg" />

---

### ⚠️ Fraud Detection Model (Confusion Matrix & ROC-AUC)
<img width="85%" alt="Confusion Matrix" src="https://raw.githubusercontent.com/dipondasrahul-blip/Consumer-Complaint-Analysis-NLP-ML/main/Confusion_Matrix.jpg" />

</div>

---

## 🧰 Tech Stack
`Python` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn`  
`NLTK (VADER)` · `Gensim (LDA)` · `Scikit-learn (RandomForest)` · `PyLDAvis`

---

## 🏁 Outcome
Built an AI-driven framework for real-time consumer complaint monitoring.  
The model supports **regulators, policymakers, and financial institutions** in detecting fraud and improving customer experience transparency.

---

## 👨‍💻 Author
**Sayer Bin Shafi**  
🎓 MBA in Business Analytics (STEM), Midwestern State University  
📍 Texas, USA  
📧 [dipondasrahul@gmail.com](mailto:dipondasrahul@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/sayershafi) | [GitHub](https://github.com/sayershafi)

---

## 🧾 Tags
`#AI` `#NLP` `#MachineLearning` `#FraudDetection` `#DataScience` `#FinancialAnalytics` `#Python`

---
