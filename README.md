# 🏘️ Texas House Price Rate Analysis via Google Trends

This project explores whether Google search trends—specifically search interest in **jobs, schools, and businesses**—can help predict changes in **house price rates** across eight major cities in Texas. Using Python and multiple linear regression, the analysis focuses on the statistical relationship between public search behavior and real estate market volatility.

---

## 📍 Cities Analyzed

- Dallas
- Austin
- Houston
- San Antonio
- Lubbock
- Waco
- Laredo
- El Paso

---

## 🎯 Objective

To determine whether search trends (Google Trends data) for **jobs, schools, and businesses** can predict **monthly house price rate changes** across major cities in Texas.

---

## 🔍 Data Sources

- **Google Trends** — Search interest in Jobs, Schools, and Businesses
- **Zillow** — Monthly House Price data for Texas cities

---

## 🧰 Tools & Methods

- Data Cleaning & Reshaping (Pandas)
- Exploratory Data Analysis:
  - Boxplots (city-wise volatility)
  - Heatmaps (correlation among cities)
- Multiple Linear Regression (StatsModels)
- Libraries used:
  - `pandas`, `matplotlib`, `seaborn`, `statsmodels`, `openpyxl`

---

## 📊 Key Insights

### 📌 Boxplot Analysis:
- **Austin** had the **widest variability** in house price rates, with frequent positive spikes and occasional negative dips.
- **Dallas, Houston, and Laredo** showed more **stable housing trends**.
- **El Paso and Lubbock** had smaller interquartile ranges but included **occasional extreme outliers**.

### 📌 Heatmap Analysis:
- Strongest correlations:
  - Dallas & Houston: **0.99**
  - Houston & Waco: **0.99**
- Weakest correlations:
  - Austin & Laredo: **0.23**
  - Austin & Waco: **0.41**

### 📌 Regression Analysis:
- **Aggregate model** showed:
  - F-statistic = **4.88**, p-value = **0.004** → statistically significant
  - **Adjusted R² = 0.165** → low explanatory power
- Of the variables:
  - Only **"business" searches** had significant predictive power (p = **0.002**) with a **negative coefficient**, indicating higher business searches slightly decrease house rate changes.

---

## 📂 Files Included

- `FinalPriceRegression.ipynb` – Python notebook with full code, visuals, and regression results
- `ADTA 5230 Final Paper Draft.docx` – Report detailing methodology, insights, and interpretations
- `requirements.txt` – Python dependencies

---

## 📬 Contact

**Amey Tillu**  
📧 ameytillu1994@gmail.com  
🔗 [GitHub Profile](https://github.com/Ameyt1994)

---

## 📝 License

This project is licensed under the **MIT License** – feel free to reuse and build upon it with attribution.
