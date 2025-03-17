# Data Engineering Foundations 📊🔧  
[![Python](https://img.shields.io/badge/Python-3.10+-blue)](https://www.python.org/) [![R](https://img.shields.io/badge/R-4.3.2-276DC3)](https://www.r-project.org/)  
**Educational repository covering financial data analysis, ETL workflows, and core data engineering skills.**  

---

## 🛠️ Core Content  

### **Python Stack**  
| Topic                      | Key Libraries/APIs         |  
|----------------------------|----------------------------|  
| Financial Analysis         | Pandas, NumPy              |  
| Data Preprocessing         | COVID-19 Spain Dataset     |  
| API Integration            | Yahoo Finance              |  

### **R Essentials**  
| File          | Focus                          |  
|---------------|--------------------------------|  
| `ggplot.R`    | Data visualization             |  
| `dplyr.R`     | Data manipulation              |  
| `pivot.R`     | Table transformations          |  

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
