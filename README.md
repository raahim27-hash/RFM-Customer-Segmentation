## Task 3 – RFM Customer Segmentation Analysis  

This project is part of my **Elevvo Data Analytics Internship**, where I performed **Customer Segmentation using RFM (Recency, Frequency, Monetary) analysis**.  
The objective was to understand customer behavior patterns and group them into actionable segments for **targeted marketing**.  

---

## 📊 Dataset  
- **Source:** [Online Retail Dataset - UCI](https://archive.ics.uci.edu/ml/datasets/Online+Retail)  
- **Details:** Contains ~500,000 transactions from a UK-based online retailer between 2010–2011.  

---

## 🛠 Tools & Technologies Used  

| Tool        | Purpose                          |
|-------------|----------------------------------|
| Python      | Data manipulation and analysis   |
| Pandas      | Handling tabular data            |
| Seaborn     | Data visualization               |
| Matplotlib  | Plot customization               |
| Jupyter/Colab | Development environment        |

---

## 🔑 Key Steps Performed  

### 1. Data Loading & Cleaning  
- Removed missing values and cancelled orders.  
- Ensured correct date/time format and numeric conversion.  

### 2. RFM Metric Calculation  
- **Recency:** Days since last purchase  
- **Frequency:** Number of repeat purchases  
- **Monetary:** Total amount spent  

### 3. Scoring & Segmentation  
- Scaled RFM metrics from **1 to 4 using quantiles**.  
- Created combined RFM scores and assigned customer segments:  
  - Champions  
  - Loyal Customers  
  - At Risk  
  - Lost  
  - New Customers, etc.  

### 4. Visual Analysis  
- Count plots for customer segments  
- Boxplots of **Monetary by Segment**  
- Heatmaps for **R vs F scores**  
- Cluster trends via colored distributions  

---

## 📈 Visualizations  

| Chart Type  | Purpose                                |
|-------------|----------------------------------------|
| Barplot (Segment Dist.) | Show distribution of customer types |
| Boxplot (Monetary)      | Understand value by segment |
| Heatmap (R vs F)        | Visualize relationship scores |

All visualizations were designed with **clean, professional themes** and color schemes to enhance readability and storytelling.  

---

## 💡 Key Insights  
- **Champions** are top customers spending the most recently and frequently.  
- **At Risk** and **Lost** customers may need re-engagement campaigns.  
- **New Customers** and **Potential Loyalists** show promise for nurturing.  
- **High Monetary but Low Frequency** customers may indicate occasional big spenders.  

---

## 📂 Files Included  
- `Customer_Segmentation_Using_RFM_Analysis.ipynb` — Code notebook  
- `Online Retail.xlsx` — Dataset used for exploration  
- `README.md` — Documentation  
- `rfm_segment_summary.csv` — Summary of customer segments
- `rfm_customers_with_rfm_and_actions.csv` — Customers along with rfm actions  

---

---
## 📄 License
This project is licensed under the MIT License.

---
## 👤 Author: Raahim Muzaffar Ishtiaq
🔗 GitHub: github.com/raahim27-hash/RFM-Customer-Segmentation/

🤝 Special Thanks: Elevvo Pathways

---
