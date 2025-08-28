# 🛍️ Customer Segmentation with RFM Analysis  

## 📌 Project Overview  
This project applies **RFM Analysis (Recency, Frequency, Monetary)** to segment customers using the **Online Retail Dataset (UCI)**.  
The goal is to understand customer behavior, group them into meaningful **segments**, and suggest **marketing strategies** for each group.  

---

## 📂 Files Included  
- 📒 `Task3_RFM_Segmentation_UPDATED.ipynb` → Jupyter Notebook with full analysis  
- 📊 `rfm_segment_summary.csv` → Segment-level summary with insights & strategies  
- 👥 `rfm_customers_with_rfm_and_actions.csv` → Customer-level RFM scores, segments & recommended actions  

---

## 🛠️ Tech Stack  
- **Python 3.x**  
- 🐼 Pandas → Data manipulation  
- 📈 Matplotlib / Seaborn → Data visualization  
- 🧮 Feature Engineering → RFM scoring & segmentation  

---

## 🔎 Methodology  

### 1️⃣ Data Preparation  
✔️ Load Online Retail dataset  
✔️ Handle missing values & duplicates  
✔️ Filter completed transactions  

### 2️⃣ RFM Feature Engineering  
- **Recency (R):** Days since last purchase  
- **Frequency (F):** Number of transactions  
- **Monetary (M):** Total money spent  

### 3️⃣ Scoring & Segmentation  
Each customer gets a score (1–5) for R, F, M.  
We then map them into segments such as:  
- 👑 **Champions** → recent, frequent, big spenders  
- 💎 **Loyal Customers** → regular buyers, good value  
- 🌱 **Potential Loyalists** → promising new customers  
- ⚠️ **At Risk** → haven’t purchased in a while  
- 💤 **Need Attention** → disengaged customers  

### 4️⃣ Marketing Strategies  
- **Champions** → Loyalty rewards, early access  
- **Loyal Customers** → VIP offers, discounts  
- **Potential Loyalists** → Special promotions, nurturing  
- **At Risk** → Win-back campaigns, personalized deals  
- **Need Attention** → Engagement campaigns, incentives  

---

## 📊 Visualizations  

### Segment Distribution  
![Segment Bar Chart](assets/segment_distribution.png)  

### RFM Heatmap  
![RFM Heatmap](assets/rfm_heatmap.png)  

### Revenue by Segment  
![Revenue Chart](assets/revenue_by_segment.png)  

*(These plots are generated automatically when running the notebook. Place them in an `assets/` folder for GitHub rendering.)*  

---

## 🚀 How to Run  

```bash
# 1. Clone the repo or download files
git clone <your-repo-link>

# 2. Install dependencies
pip install pandas matplotlib seaborn

# 3. Open the Jupyter Notebook
jupyter notebook Task3_RFM_Segmentation_UPDATED.ipynb

