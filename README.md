# 🧮 Retail Sales Data Cleaning and Insights — Superstore Dataset

## 📄 Overview
This project demonstrates my ability to clean, transform, and visualize real-world sales data using Python.  
The dataset comes from Kaggle’s [Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final), which simulates retail transactions across U.S. states.

## 🧰 Tools & Libraries
- **Python** (Pandas, NumPy)
- **Matplotlib & Seaborn** for visualization
- **Jupyter Notebook** for analysis presentation

## ⚙️ Steps Performed
1. **Data Loading & Inspection:** Checked data types, missing values, and duplicates.  
2. **Data Cleaning:**  
   - Dropped non-informative columns (e.g., `Country`).  
   - Converted date columns to `datetime`.  
   - Removed outliers in `Sales` and `Profit`.  
3. **Feature Engineering:** Created new fields such as *“Time to ship”* and *“Season.”*  
4. **Exploratory Analysis:**  
   - Shipping time distribution by state and mode.  
   - Most ordered products by category.  
   - Seasonal sales and profit trends.  
5. **Visualization:** Developed multiple charts and summaries for business insights.

## 📊 Key Insights
- **Standard Class** shipping generally takes longer, especially in remote states (e.g., Maine, Wyoming).  
- **Office Supplies** (Binders, Paper) are the top-selling products across most states.  
- **Summer** sees the highest order volumes.  
- **Profit** is uneven — certain categories drive high revenue but low margins.

## 🧠 What This Project Demonstrates
- End-to-end data wrangling and cleaning workflow.  
- Exploratory analysis and visualization for business interpretation.  
- Ability to present findings in a clear, client-friendly format.

## 📂 Repository Structure
```
│
├── Sales_Data_Analysis.ipynb   # Main analysis notebook
├── superstore_cleaned.csv      # Cleaned dataset (optional)
└── README.md                   # Project summary and insights
```

## 📈 Preview

Below are sample visuals from the analysis:

**1. Top Ordered Sub-Categories by State and Category**  
![Top Subcategories](./Screenshot_2025-10-31_165329.png)

**2. States with the Longest Shipping Time**  
![Longest Shipping Time](./Screenshot_2025-10-31_165352.png)

**3. Profit by Season (Positive vs. Negative Profit)**  
![Profit by Season](./Screenshot_2025-10-31_165415.png)




## 🚀 Next Steps
Future improvements will focus on:
- Enhancing code structure (warning-free, efficient slicing)
- Adding dashboard interactivity (e.g., Streamlit)
- Automating reporting and exporting visuals
