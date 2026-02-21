# 🌍 Global Electricity Access & Economic Indicators Analysis

**Kaggle | Python | MIT License | Jupyter Notebook**

---

## 📌 Project Overview

A comprehensive data analysis project exploring the relationship between electricity access, economic development, and population dynamics across **200+ countries (2000–2024)**.

This analysis supports **UN Sustainable Development Goal 7 (SDG-7)** — ensuring affordable and clean energy for all by 2030.

---

## 🎯 Key Objectives

- Analyze global electricity access trends over 25 years  
- Identify correlations between GDP and electricity infrastructure  
- Forecast future electricity access rates using machine learning  
- Assess country progress toward SDG-7 targets  
- Cluster countries based on electrification and economic profiles  

---

## 📊 Dataset Information

### Source
World Bank Open Data Indicators (2000–2024)

### Features

| Column | Description | Unit | Indicator Code |
|--------|------------|------|----------------|
| country | Country or region name | — | — |
| date | Year of observation | Year | — |
| GDP_Per_Capita_Current_USD | GDP per capita | USD | NY.GDP.PCAP.CD |
| Total_Population | Total population count | Count | SP.POP.TOTL |
| Population_Female_Percentage | Female share of population | % | SP.POP.TOTL.FE.ZS |
| Population_Male_Percentage | Male share of population | % | SP.POP.TOTL.MA.ZS |
| Electricity_Access_Urban_Percentage | Urban electricity access | % | 1.3_ACCESS.ELECTRICITY.URBAN |
| Electricity_Access_Rural_Percentage | Rural electricity access | % | 1.2_ACCESS.ELECTRICITY.RURAL |
| Total_Electricity_Output_GWh | Net electricity generation | GWh | 4.1.1_TOTAL.ELECTRICITY.OUTPUT |

### Dataset Statistics

- **Countries/Regions:** 200+  
- **Time Period:** 2000–2024  
- **Total Records:** ~5,000  
- **Missing Data:** Primarily in electricity metrics (2017–2024)

---

## 🔬 Analysis Components

### 🟢 Beginner Level

- 100% Access Achievement: Countries with universal electricity access by 2015  
- Rural Access Trends: Global average rural electricity growth (2000–2016)  
- GDP Rankings: Top 10 countries by GDP per capita (2023)  
- Population Growth: Global population increased from 6.1B to 8.1B+  

---

### 🟡 Intermediate Level

- GDP–Electricity Correlation: Strong positive correlation (r > 0.7)  
- Fastest Growing Regions: South Asia & East Africa (>40 percentage point improvement)  
- Output vs Population: Log-log relationship analysis  
- Urban–Rural Gap: Largest disparities in Sub-Saharan Africa  

---

### 🔴 Advanced Level

- Forecasting (2025–2030): Linear Regression & Time Series analysis  
- Country Clustering: K-Means clustering into 4 distinct groups  
- SDG-7 Assessment: 50–70 countries identified as off-track  

---

## 📈 Key Findings

### ✅ Main Insights

- Strong link between GDP per capita and electricity access  
- Sub-Saharan Africa shows the largest urban–rural disparities  
- Rural access increased globally from ~70% to ~85% (2000–2016)  
- Many developing nations may not achieve universal access by 2030  

### 🌍 Country Clusters

- Group 1: Fully electrified high-income countries  
- Group 2: Transitioning middle-income countries  
- Group 3: Low-income countries with limited access  
- Group 4: Emerging economies with rapid electrification growth  

---

## 🛠️ Technologies Used

### Programming & Analysis
- Python 3.8+  
- Pandas  
- NumPy  
- Scikit-learn  

### Visualization
- Matplotlib  
- Seaborn  
- Plotly  
- Choropleth Maps  

### Machine Learning
- Linear Regression  
- K-Means Clustering  
- Time Series Analysis  

---

## 🚀 Getting Started

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn
```
### Clone Repository
```
git clone https://github.com/yourusername/global-electricity-access-analysis.git
cd global-electricity-access-analysis
```
### Download Dataset
```
kaggle datasets download -d muhammadaammartufail/global-electricity-access-and-economic-indicators
unzip global-electricity-access-and-economic-indicators.zip
```
## Run Notebook
```
jupyter notebook global_electricity_analysis.ipynb
```
### 📂 Project Structure
```
global-electricity-access-analysis/
│
├── global_electricity_analysis.ipynb
├── data/
│   └── electricity_access.csv
├── visualizations/
├── models/
├── README.md
└── LICENSE
```
## 🎯 Future Work

- LSTM Deep Learning models for forecasting

- Real-time dashboard (Streamlit / Dash)

- Regional deep-dive analysis

- Policy recommendation modeling

- CO₂ emissions integration

- Investment requirement estimation
## 👥 Contributors

- Muhammad Aammar Tufail — Lead Data Analyst

- Hammad Zahid — Collaborator
## 📝 License

- This project is licensed under the MIT License.
<p><strong>Author:</strong> Muhammad Aammar Tufail</p>
<p><strong>Collaborator:</strong> Hammad Zahid</p>
<p><strong>Dataset Source:</strong> Global Electricity Access & Economic Indicators 2</p>
<p><strong>Analysis Date:</strong> 2026</p>

<hr style="border: 1px solid #4fc3f7;">

<p>📧 <strong>Email:</strong> 
<a href="mailto:mrhammadzahid24@gmail.com" 
   style="color:#4fc3f7; text-decoration:none;">
   mrhammadzahid24@gmail.com
</a>
</p>

<p>🔗 <strong>LinkedIn:</strong> 
<a href="https://www.linkedin.com/in/hammad-zahid-xyz" target="_blank"
   style="color:#4fc3f7; text-decoration:none;">
   linkedin.com/in/hammad-zahid-xyz
</a>
</p>

<p>🐦 <strong>Twitter (X):</strong> 
<a href="https://x.com/zahid_hamm57652" target="_blank"
   style="color:#4fc3f7; text-decoration:none;">
   @zahid_hamm57652
</a>
</p>

<p>💻 <strong>GitHub:</strong> 
<a href="https://github.com/Hamad-Ansari" target="_blank"
   style="color:#4fc3f7; text-decoration:none;">
   github.com/Hamad-Ansari
</a>
</p>
## 📚 Citation
@dataset{tufail2024electricity,
  title={Global Electricity Access & Economic Indicators Analysis},
  author={Tufail, Muhammad Aammar and Zahid, Hammad},
  year={2024},
  publisher={Kaggle},
  url={https://www.kaggle.com/code/hammadansari7/global-electricity-access-economic-indicators}
}
## ⭐ Support

If you found this helpful:

- ⭐ Star the repository

- 🔀 Fork the project

- 📢 Share it

- 💬 Provide feedback
Made with ❤️ for SDG-7: Affordable and Clean Energy for All
Together, we can achieve universal electricity access by 2030.

---

If you want, I can now:
- Optimize it for a **Kaggle dataset page**
- Or create a more **minimal, recruiter-friendly GitHub version** 🚀
