# Data Engineering & Science Foundations 📊🔬 
[![Python](https://img.shields.io/badge/Python-3.10+-blue)](https://www.python.org/) [![Scikit-Learn](https://img.shields.io/badge/ScikitLearn-1.3.2-orange)](https://scikit-learn.org/)  
**End-to-end data workflows: ETL pipelines, machine learning, and statistical analysis.**  

---

## 🛠️ Core Content  

### **Data Engineering**  
| Topic                      | Key Libraries/APIs         |  
|----------------------------|----------------------------|  
| Financial Analysis         | Pandas, NumPy              |  
| API Integration            | Yahoo Finance              |  
| COVID-19 Preprocessing     | Spain Health Data (.csv)   |  

### **Data Science Introduction**  
| Algorithm               | Implementation              |  
|-------------------------|-----------------------------|  
| Linear Regression       | `sklearn.linear_model`      |  
| Logistic Regression     | Odds ratio visualization    |  
| Decision Trees          | Gini impurity analysis      |  
| K-Means Clustering      | Elbow method (WCSS)         |  
| PCA                     | Dimensionality reduction    |  

---

## 🔑 Key Projects
**1. COVID-19 Spain Preprocessing**
  - Missing value imputation
  - Time-series normalization
  - Export to optimized Parquet format
    
**2. Yahoo Finance API Pipeline**
```bash
from yfinance import Ticker  
msft = Ticker("MSFT")  
hist = msft.history(period="1y")
```
---

## 🛠️ Tools & Workflow
**1. Development:**
  - Jupyter Lab + VSCode
  - RStudio for statistical analysis
    
**2. Dependencies:**
```bash
pip install yfinance pandas numpy  
Rscript -e "install.packages(c('tidyverse', 'lubridate'))"
```
---

## 📜 Certification 
  - **Autodidactic Validation:** Self-authored documentation & datasets
  - **Open-Source:** MIT Licensed  

Educational content under MIT License.
