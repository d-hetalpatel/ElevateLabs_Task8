# ElevateLabs_Task8
Clustering with K-Means
# 🛍 Customer Segmentation with K-Means (Mall_Customers Dataset)

## 📖 About
This project uses the **Mall_Customers dataset** for customer segmentation.  
K-Means clustering is applied to group customers based on **demographics** and **spending behavior**.  

---

## 🎯 Objectives
- Segment customers into distinct groups  
- Identify high-value vs. low-value customers  
- Visualize clusters for better business insights  

---

## 📂 Dataset
- **Source:** Mall_Customers.csv (typical Kaggle dataset)  
- **Features:**
  - `CustomerID`  
  - `Gender` (Male/Female → encoded)  
  - `Age`  
  - `Annual Income (k$)`  
  - `Spending Score (1-100)`  

---

## ⚙️ Methodology
1. **Load and preprocess dataset** (encode Gender)  
2. **Feature selection**: Annual Income, Spending Score (and optionally Age, Gender)  
3. **Apply K-Means clustering**  
4. **Find optimal K** using the **Elbow Method**  
5. **Visualize clusters** with scatter plots  
6. **Evaluate cluster quality** using **Silhouette Score**  

---

## 📊 Results
- Best number of clusters found ≈ **5**  
- Silhouette Score ~ **0.55** (moderate clustering quality)  
- Distinct groups observed:  
  - 🟢 High Income – High Spending  
  - 🔵 High Income – Low Spending  
  - 🟠 Low Income – High Spending  
  - 🔴 Average customers  

---
