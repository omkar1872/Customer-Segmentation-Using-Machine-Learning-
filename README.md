# Customer Segmentation using Machine Learning

## 📌 Overview
This project applies **unsupervised learning** techniques to segment customers based on their purchasing behavior. The goal is to identify different customer groups, enabling businesses to optimize their marketing strategies and personalize customer experiences.
![Cluster Visualization](https://github.com/omkar1872/Customer-Segmentation-Using-Machine-Learning-/blob/main/Images/Customer-segmentation.png)

---

## 🛠 Technologies Used
- **Python** 🐍  
- **Pandas & NumPy** (Data processing)  
- **Matplotlib & Seaborn** (Data visualization)  
- **Scikit-learn** (Machine Learning - Clustering)  
- **Jupyter Notebook / Google Colab** (Implementation)  

---

## 📊 Dataset
The project uses the **Mall Customers Dataset**, which contains information about customers’ age, gender, income, and spending habits.

**Features:**
- **Customer ID** – Unique customer identifier  
- **Gender** – Male / Female  
- **Age** – Age of the customer  
- **Annual Income (k$)** – Income in thousands of dollars  
- **Spending Score (1-100)** – Score assigned based on spending patterns  

📥 **Dataset Source:** [Kaggle - Mall Customers Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)  

---

## ⚡ Approach

### 1️⃣ Data Preprocessing
✔ Load the dataset  
✔ Handle missing values (if any)  
✔ Normalize numerical features for better clustering  

### 2️⃣ Exploratory Data Analysis (EDA)
✔ Understand customer distributions (age, income, spending score)  
✔ Identify relationships between variables using scatter plots  

### 3️⃣ Clustering Techniques
✔ **K-Means Clustering** – Groups customers into `k` clusters using the **Elbow Method**  
✔ **Hierarchical Clustering** – Uses **dendrograms** to visualize group relationships  
✔ **DBSCAN** – Identifies clusters based on density  

### 4️⃣ Results & Insights
✔ Visualize customer groups using scatter plots  
✔ Interpret each cluster's behavior for marketing strategies  

---


## 📊 Results & Visualizations

### **1️⃣ Elbow Method for Optimal Clusters**
The **Elbow Method** is used to determine the optimal number of clusters for K-Means.

![Elbow Method](https://github.com/omkar1872/Customer-Segmentation-Using-Machine-Learning-/blob/main/Images/download%20(3).png)

---

### **2️⃣ Customer Segments (K-Means Clustering)**
This plot shows the different customer segments identified using K-Means clustering.

![Cluster Visualization](https://github.com/omkar1872/Customer-Segmentation-Using-Machine-Learning-/blob/main/Images/download%20(1).png)

---



