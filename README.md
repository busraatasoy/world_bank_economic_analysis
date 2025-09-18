# 🌍 World Economic Report

This project analyzes global economic indicators from the `World Bank` and `United Nations (UN)` to uncover key trends in global development.
The dataset covers `1960–2018` and includes metrics like `GDP per capita`, `electricity consumption`, `life expectancy`, `population by region`, and `Human Development Index (HDI)`.

---

## 📌 Project Objectives

**1. Data Preparation & QA**
- Load and clean World Bank and UN datasets
- Calculate population from GDP and GDP per capita
- Merge HDI data for 2014 using ISO3 codes

**2. Data Transformation**
- Create pivot tables for GDP by region over time
- Prepare dataframes for visualization

**3. Data Analysis & Visualization**
- Analyze trends in GDP growth by region
- Explore correlation between GDP per capita and HDI
- Compare population growth across regions
- Visualize electricity consumption over time

**4. Create a Final Report**
- Assemble all created visualizations into a single figure using matplotlib’s GridSpec
- Row 1 → Place the stacked area charts
- Row 2 → Place the bubble chart
- Row 3 → Place the bar chart and scatter plot side by side
- Add an overall figure title and descriptive text annotations for each row to give context
- Encourage creative layouts, color schemes, and additional insights

---

## 📁 Project Structure
```bash
world_bank_economic_analysis/
│
├── data/ # Raw datasets (.xlsx, .csv)
├── world_bank_economic_analysis.ipynb # Jupyter notebooks (main analysis here)
├── visuals/ # Exported charts and figures
└── README.md
```

---

## ⚙️ Setup & Usage
To run this project locally:

1. Make sure you have Python 3.9+ installed.
2. Install required packages (if not installed):

```bash
pip install pandas numpy matplotlib seaborn
```

3. Open the Jupyter Notebook:
```bash
jupyter notebook "world_bank_economic_analysis.ipynb"
```
4. Run all cells sequentially to generate the visualizations.

## 📌 Key Insights
- GDP and population have grown significantly in the 20th and 21st centuries.
- East Asia has become a major economic contributor by 2018.
- Life expectancy generally increases with GDP per capita.
- HDI shows significant regional disparities; developed regions enjoy higher HDI scores.
- Electricity consumption is a key driver of development, enabling higher productivity.


## 📚 References
- [Link of Project:](https://mavenanalytics.io/guided-projects/world-economic-report)

- [View Project Badge:](https://certificates.mavenanalytics.io/3ccb45e0-b371-4465-a517-b6e1fe056e70)
