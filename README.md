# PRODIGY_DS_01
# 📊 Power BI – World Bank Population Visualization

## ✅ Task-01
Create a bar chart or histogram to visualize the distribution of a categorical or continuous variable,  
using World Bank total population data.

---

## 📦 Dataset
- Source: [World Bank – Total Population (SP.POP.TOTL)](https://data.worldbank.org/indicator/SP.POP.TOTL)
- File used: `API_SP.POP.TOTL_DS2_en_csv_v2_38144.csv`

---

## 🛠 Today's Progress – 07 July 2025

### 🔹 Data Preparation in Power BI
- Imported the CSV into Power BI Desktop.
- Removed extra metadata/header rows from the top.
- Renamed columns to meaningful names:
  - `Data Source → Country Name`
  - `World Development Indicators → Country Code`
  - `_1 → Indicator Name`
  - `_2 → Indicator Code`
  - `_3 → 1960` and so on up to `2024`.
- Removed unnecessary columns:
  - `Indicator Name` and `Indicator Code`.

### 🔄 Data Transformation
- Selected all year columns (1960–2024).
- Used **Unpivot Columns** to convert them into tidy format:
  - `Attribute → Year`
  - `Value → Population`.

- Resulting table now has:
| Country Name | Country Code | Year | Population |

---

## 📊 Visualization Plan
- **Option 1:** Bar chart – Top N countries by population in 2022.
- **Option 2:** Histogram – Number of countries by population range.

---

## 📁 Files added today
- Original dataset CSV file.
- Work-in-progress Power BI file (`.pbix`).
- This README.md file.

---

✅ **Next steps:**
- Finalize visuals in Power BI.
- Customize formatting and add data labels.
- Upload final screenshots or exported visuals.
- Share on LinkedIn with a summary of learning.

---

Progress by Flint Dias – Data Science Intern at Prodigy InfoTech.




✅ Today's Progress - 09-07-2025

Loaded global population dataset from CSV (World Bank data).

Cleaned and transformed data:

Removed top rows and unnecessary columns.

Unpivoted year columns to create tidy structure (Country, Year, Population).

Fixed data types and renamed columns.

Done with first track 


















