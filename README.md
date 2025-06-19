# 🌍 Greenhouse Gas Emissions Analysis (AI Internship Project)

This repository contains the data preprocessing work for the Greenhouse Gas Emission project as part of the **AICTE - Shell - Edunet Foundation Green Skills Internship (2025)**.

## 📌 Project Objective

To analyze supply chain emission factors from various U.S. industries and commodities between **2010 and 2016**. The goal is to prepare this data for further **machine learning modeling**, enabling better understanding and prediction of emission trends.

---

## 🗃️ Dataset Details

- **Source File:** `SupplyChainEmissionFactorsforUSIndustriesCommodities.xlsx`
- **Data Range:** 2010 to 2016
- **Sheets:** 2 per year (`Detail_Commodity` and `Detail_Industry`)
- **Key Columns:**
  - Emission Factors (with/without margin)
  - DQ (Data Quality) indicators
  - Commodity/Industry name and code
  - Year and Source type

---

## ✅ Tasks Completed (Data Preprocessing)

- [x] Combined 14 sheets into a single DataFrame using `pandas`
- [x] Added `Year` and `Source` columns for context
- [x] Stripped extra spaces from column names
- [x] Renamed long column names for easier readability
- [x] Removed completely empty columns like `Unnamed: 7`
- [x] Checked for and cleaned missing values and duplicates
- [x] Exported cleaned data as `Cleaned_GHG_Data.csv`

---

## 🧪 Technologies Used

- Python 3.x
- Jupyter Notebook
- `pandas`, `numpy`
- `openpyxl` for Excel reading
- `matplotlib` & `seaborn` (for future visualization)

---

## 📊 Next Steps

- Perform Exploratory Data Analysis (EDA)
- Visualize emission trends over time
- Build ML models for predicting emission factors
- Evaluate and optimize model performance

---

## 🙋‍♀️ Author

**Bhumika Dash**  
Computer Science Engineering  
AICTE - Edunet - Shell Green Skills Intern (June–July 2025)

---

## 📄 License

This project is part of an academic internship and is intended for educational and research purposes only.

