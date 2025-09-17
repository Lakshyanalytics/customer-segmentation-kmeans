# Customer Segmentation using K-Means Clustering

## 📌 Overview  
This project applies **K-Means clustering** to segment customers into meaningful groups based on demographics, income, purchasing behavior, and engagement.  
The goal is to identify distinct customer profiles that businesses can target with tailored marketing strategies, ultimately improving **campaign effectiveness, retention, and resource allocation**.

---

## 🎯 Problem Statement  
Businesses often struggle to understand their diverse customer base. By clustering customers into segments, companies can:  
- Design targeted marketing campaigns  
- Optimize resource allocation  
- Improve product recommendations  
- Develop retention and loyalty strategies  

---

## 📊 Dataset  
- **Source**: [Kaggle – Customer Segmentation: Clustering](https://www.kaggle.com/)  
- **Key Features**:  
  - `Income`: Annual income of customers  
  - `Recency`: Days since last purchase  
  - `MntWines, MntFruits, ... MntGoldProds`: Spending on product categories  
  - `NumDealsPurchases, NumWebPurchases, NumCatalogPurchases, NumStorePurchases`: Channel-specific purchase activity  
  - `NumWebVisitsMonth`: Website engagement  
  - `Response`: Campaign response  

---

## 🛠️ Methodology  
1. Data cleaning & preprocessing  
2. Feature scaling  
3. Optimal cluster selection using **Elbow Method** & **Silhouette Score**  
4. K-Means clustering implementation  
5. Profiling and interpreting customer segments  

---

## 📈 Results – Cluster Profiles & Business Insights  

- **Cluster 0**: Mature, middle-income customers with steady spending  
- **Cluster 1**: Elderly, low-income, low-engagement segment  
- **Cluster 2**: Affluent, middle-aged, high purchasing power (premium targets)  
- **Cluster 3**: Wealthy seniors, high discretionary spending, prefer offline stores  
- **Cluster 4**: Younger, low-income, recently active but low spenders  
- **Cluster 5**: Budget-conscious younger customers, more digitally active  

---

## 🚀 How to Run  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/customer-segmentation-kmeans.git
   cd customer-segmentation-kmeans

pip install -r requirements.txt

jupyter notebook Customer_Segmentation_KMeans.ipynb

## 📬 Contact
Author: Lakshya Rana 

📧 Email: lakshyarana1806@gmail.com

🔗 [LinkedIn](https://www.linkedin.com/in/lakshyarana01)
