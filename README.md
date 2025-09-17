# Customer Segmentation using K-Means Clustering

## 📌 Overview  
This project applies **K-Means clustering** to segment customers into meaningful groups based on demographics, income, purchasing behavior, and engagement.  
The segmentation reveals distinct customer profiles that can be targeted with tailored marketing strategies, ultimately improving **campaign effectiveness, retention, and resource allocation**.  

---

## 🎯 Problem Statement  
Businesses often struggle to design one-size-fits-all strategies due to diverse customer bases.  
By segmenting customers, companies can:  
- Design targeted marketing campaigns  
- Optimize resource allocation  
- Improve product recommendations  
- Develop loyalty and retention strategies  

---

## 📊 Dataset  
- **Source**: Kaggle – Customer Segmentation: Clustering  
- **Key Features**:  
  - `Income` – Annual income  
  - `Recency` – Days since last purchase  
  - Spending on product categories (`MntWines`, `MntFruits`, … `MntGoldProds`)  
  - Channel-specific purchase activity (`NumDealsPurchases`, `NumWebPurchases`, `NumCatalogPurchases`, `NumStorePurchases`)  
  - Website engagement (`NumWebVisitsMonth`)  
  - Campaign response (`Response`)  

---

## 🛠️ Methodology  
1. **Data Cleaning & Preprocessing** – handled missing values, formatted columns  
2. **Feature Scaling** – standardized numerical features for clustering  
3. **Optimal Cluster Selection** – used Elbow Method and Silhouette Score  
4. **K-Means Clustering** – grouped customers into 6 distinct clusters  
5. **Profiling** – analyzed demographics, spending, and engagement within each cluster  

---

## 📈 Cluster Profiles & Insights  

### Cluster 0 (430 customers)  
- Avg Age: ~59.8 years  
- Avg Income: ~59,684  
- Avg Total Spending: ~892  
- Num Web Purchases: ~7.88  
- Num Store Purchases: ~7.93  
- Num Web Visits/Month: ~6.39  
- Recency: ~46.6  
**Insight**: Mature, middle-income customers with steady spending habits across channels.  

---

### Cluster 1 (319 customers)  
- Avg Age: ~68.0 years  
- Avg Income: ~43,447  
- Avg Total Spending: ~171 *(lowest among clusters)*  
- Num Web Purchases: ~2.59  
- Num Store Purchases: ~4.02  
- Num Web Visits/Month: ~5.38  
- Recency: ~51.9  
**Insight**: Elderly, low-income, low-engagement segment. Price-sensitive, less responsive to campaigns.  

---

### Cluster 2 (333 customers)  
- Avg Age: ~46.1 years  
- Avg Income: ~75,463  
- Avg Total Spending: ~1307  
- Num Web Purchases: ~4.75  
- Num Store Purchases: ~8.81  
- Num Web Visits/Month: ~2.78  
- Recency: ~48.5  
**Insight**: Affluent, middle-aged with strong purchasing power. Best target for premium campaigns.  

---

### Cluster 3 (313 customers)  
- Avg Age: ~68.9 years  
- Avg Income: ~77,134 *(highest)*  
- Avg Total Spending: ~1204  
- Num Web Purchases: ~4.52  
- Num Store Purchases: ~8.22  
- Num Web Visits/Month: ~2.50  
- Recency: ~52.7  
**Insight**: Wealthy seniors with high discretionary spending. Prefer offline/traditional stores.  

---

### Cluster 4 (449 customers)  
- Avg Age: ~48.8 years  
- Avg Income: ~33,008  
- Avg Total Spending: ~116  
- Num Web Purchases: ~2.18  
- Num Store Purchases: ~3.27  
- Num Web Visits/Month: ~6.65  
- Recency: ~24.1 *(most recently active)*  
**Insight**: Younger, low-income, recently active customers. Hard to monetize without budget-friendly offers.  

---

### Cluster 5 (372 customers)  
- Avg Age: ~49.1 years  
- Avg Income: ~32,697  
- Avg Total Spending: ~116 *(similar to Cluster 4)*  
- Num Web Purchases: ~2.33  
- Num Store Purchases: ~3.18  
- Num Web Visits/Month: ~7.06  
- Recency: ~76.7 *(least recently active)*  
**Insight**: Budget-conscious younger customers, digitally active. Can be targeted with e-commerce discounts.  

---

## 📝 Conclusion  
This analysis shows that customer behavior varies significantly across demographics, income levels, and engagement.  
- **High-value groups** (Clusters 2 & 3) should be targeted with premium campaigns and personalized loyalty programs.  
- **Price-sensitive groups** (Clusters 1, 4, 5) require budget-friendly strategies, discounts, and digital promotions.  
- **Balanced spenders** (Cluster 0) represent a stable middle segment with consistent cross-channel engagement.  

By leveraging these insights, businesses can **align marketing, improve retention, and allocate resources more effectively**.  

---

## 📌 Tech Stack

Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)

Jupyter Notebook

## 📬 Contact

**Author: Lakshya Rana**

📧 (lakshyarana1806@gmail.com)

🔗 [LinkedIn](https://www.linkedin.com/in/lakshyarana01/)

---

## 🚀 How to Run  
```bash
pip install -r requirements.txt
jupyter notebook Customer_Segmentation_KMeans.ipynb

**## 📌 Tech Stack**

Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)

Jupyter Notebook
