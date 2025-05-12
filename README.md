# 🧠 Customer Segmentation Analysis for Retail

## 🎯 Business Objective  
Reduce marketing costs by **20%** by identifying high-value customer segments using **RFM analysis** and **K-means clustering**.

This project uses **Recency, Frequency, and Monetary (RFM)** analysis to segment customers based on their purchase behavior. It's designed to help retail businesses:
- Identify their most valuable customers
- Optimize marketing strategies
- Maximize customer lifetime value

---

## 📦 Problem Statement  

Retail businesses often struggle to:
- 🎯 Target the right customers with marketing campaigns  
- 📉 Reduce churn while optimizing budget  
- 💰 Maximize customer lifetime value

---

## 📂 Dataset Description  

The dataset contains anonymized retail transaction records with the following fields:

- `CustomerID`: Unique customer identifier  
- `TransactionDate`: Date of the transaction  
- `Quantity`, `Price`: Number of items and unit price  
- `TotalAmount`: Amount spent after discount  
- `ProductCategory`, `StoreLocation`, `PaymentMethod`  

**Files included:**
- `Retail_Transaction_Dataset.csv` – Raw data  
- `Retai_Transactions_Dataset_cleaned.csv` – Cleaned data  
- `rfm_table.csv` – Final RFM segmented data  
- `customer_segmentation_analysis.ipynb` – Jupyter notebook with full code  

---

## 💡 Solution Strategy  

We performed **customer segmentation** using **RFM scoring** and **K-means clustering** to group customers based on behavior. This enables:
- Personalized targeting
- Smarter budget allocation
- Data-driven customer relationship management

---

## 🛠️ Tools & Technologies  

- **Python**: `pandas`, `matplotlib`, `scikit-learn`  
- **Power BI**: Interactive visualization dashboard  
- **SQL**: Data cleaning and aggregation  
- **Git & GitHub**: Version control and project sharing  

---

## 🔎 Methodology  

1. **Data Cleaning & Preparation**  
   - Handled missing values, date formats, and data types  
   - Calculated `TotalAmount` per transaction  

2. **RFM Feature Engineering**  
   - **Recency**: Days since last transaction  
   - **Frequency**: Number of transactions  
   - **Monetary**: Total spend  

3. **Scoring & Segmentation**  
   - Assigned scores (1–5) to each RFM feature  
   - Combined them into an `RFM_Score`  
   - Applied K-means to group customers into segments  

4. **Segments Identified**  
   - 🏆 Champions  
   - 🔁 Loyal Customers  
   - ⚠️ At Risk  
   - 💤 Hibernating  
   - 🌱 New Customers  

---

## 📊 Key Results & Insights  
Through RFM segmentation and K-means clustering, we identified six actionable customer segments:

Segment	Description
🏆 Champions	Recent (1–2 months), high frequency, high spenders. Top revenue drivers.
🔁 Loyal Customers	Recent (1–3 months), moderate to high frequency and spend. Engaged and stable.
⚠️ At Risk	Recent (2–6 months), low frequency, low spenders. Show signs of churn.
🌱 New Customers	Very recent (0–1 month), low frequency/spend. Potential to nurture.
💸 Big Spenders	Medium frequency, very high spend. Could be retained with special care.
❓ Others	Irregular, infrequent, low/average spenders. Need nurturing or reactivation.

✅## Recommendations
Segment	Actions
🏆 Champions	Offer exclusive deals, loyalty rewards, and personalized offers
🔁 Loyal Customers	Provide incentives, gather feedback, and engage regularly
⚠️ At Risk	Run win-back campaigns and offer limited-time discounts
🌱 New Customers	Send welcome offers and introductory discounts
💸 Big Spenders	Give VIP treatment, loyalty programs, and priority access
❓ Others	Track and nurture toward higher segments with targeted messaging
 

📈 **Projected Impact:**  
- 15% reduction in churn  
- 20% decrease in marketing waste  
- Higher marketing ROI through personalization  
[View Power BI Dashboard](https://app.powerbi.com/groups/me/reports/7e4e097a-76b5-479f-90f7-00d9e7f53d6a/ReportSectionf3082a9e74cd77544b86?experience=power-bi) | [Explore Full Code](notebooks/customer_segmentation.ipynb)