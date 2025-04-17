# Employment-dataset

# 🇬🇧 UK Job Change Analysis (EMSI Data)

This project analyzes employment trends across UK cities using EMSI (Economic Modeling Specialists Intl) labor market data. It focuses on changes in job counts across industries between **2011 and 2014**, using Standard Industrial Classification (SIC) codes.

## 📦 Dataset Overview

The dataset includes two levels of industry detail:

- **`1 digit` sheet**: High-level industry groupings (e.g., Manufacturing, Health, Retail)
- **`2 digit` sheet**: More detailed industry breakdowns (e.g., Food Services, Education, Construction)

### Columns Explained:

| Column         | Description                                      |
|----------------|--------------------------------------------------|
| `City`         | UK city name                                     |
| `Country`      | Country (all entries are UK)                     |
| `SIC Code`     | Industry classification code (1- or 2-digit)     |
| `Industry`     | Industry description                             |
| `Jobs 2011`    | Number of jobs in 2011                           |
| `Jobs 2014`    | Number of jobs in 2014                           |
| `Change`       | Absolute job growth or decline                   |
| `% Change`     | Relative job growth or decline (as a decimal)    |

## 🔍 Key Questions Explored

- Which UK cities experienced the most job growth from 2011 to 2014?
- Which industries saw the highest gains or losses?
- How did employment trends differ across sectors like healthcare, manufacturing, or professional services?

## 📊 Potential Use Cases

- Labor market and economic development analysis  
- City-level job growth benchmarking  
- Skills and workforce planning  
- Visualization and storytelling with employment data  

## 🧰 Tools You Can Use

- Microsoft Excel / Google Sheets  
- Python (pandas, matplotlib, seaborn)  
- Tableau / Power BI  
- SQL for relational data exploration  

I used Tableau and Python to show some of the things i found interesting such as top industries and comparisons between London and Manchester.

## 📁 File Structure

- `EMSI_JobChange_UK.xlsx`  
  - `1 digit`: High-level industry job data  
  - `2 digit`: Detailed industry job data  

## 📌 Sample Insight

> **In Aberdeen**, the "Administrative and Support Service Activities" industry added over **7,200 jobs**, marking a **32% increase** between 2011 and 2014.

## 📚 Source

Data derived from EMSI (Economic Modeling Specialists Intl), a trusted provider of labor market insights.

---

📈 Perfect for data analysis, economic research, policy-making, and academic projects!
