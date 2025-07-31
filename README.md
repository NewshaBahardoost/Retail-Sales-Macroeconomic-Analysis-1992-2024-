# 🛍️ Retail Sales & Macroeconomic Analysis (1992–2024)

This project explores how U.S. retail sales categories respond to macroeconomic factors 
(inflation, GDP growth) over time. We use machine learning and time-series mining techniques:

- **DTW + K-Means Clustering** → Group retail categories with similar temporal behavior  
- **Ridge Regression + PELT** → Estimate macroelasticities and detect structural breaks (e.g., COVID-19, 2008 recession)  
- **Visualization Dashboard** → Interactive plots of sales vs. macro indicators  

📌 **Goal:** Help policymakers, investors, and retailers understand retail sensitivity to macroeconomic regimes.

---

### **Project Structure**
- `data/` → Raw & processed datasets
- `notebooks/` → Jupyter notebooks for analysis
- `scripts/` → Modular Python code
- `results/` → Visualizations and detected breakpoints
- `report/` → Final PDF report and slides

---

### **Tech Stack**
- Python (Pandas, NumPy, Scikit-learn, ruptures, dtw-python)
- Jupyter Notebook
- Matplotlib & Seaborn
- SQL (for data extraction)
- Git for version control

---

### **How to Run**
```bash
git clone https://github.com/<yourusername>/Retail-Sales-MacroAnalysis.git
cd Retail-Sales-MacroAnalysis
pip install -r requirements.txt
jupyter notebook notebooks/01_EDA_DataCleaning.ipynb
