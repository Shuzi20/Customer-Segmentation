# **Customer Segmentation and Recommendation System**

### **Overview**
This project focuses on **customer segmentation** and the development of a **recommendation system** using transactional data from a UK-based retailer. The dataset, sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/352/online+retail), contains records of transactions between 2010 and 2011. 

Through advanced data analysis and machine learning, this project aims to enhance marketing strategies by segmenting customers into distinct groups and providing personalized recommendations.

---

### **Objectives**
1. **Data Cleaning & Transformation**: 
   - Handle missing values, duplicates, and outliers.
   - Prepare the dataset for clustering.
2. **Feature Engineering**: 
   - Develop customer-centric features for better segmentation.
3. **Data Preprocessing**: 
   - Perform scaling and dimensionality reduction for efficient clustering.
4. **Clustering Techniques**: 
   - Implement **K-Means Clustering** and **Agglomerative Clustering** for customer segmentation.
   - Evaluate cluster quality using metrics like silhouette score, Calinski-Harabasz score, and Davies-Bouldin index.
5. **Cluster Profiling**: 
   - Identify distinct customer profiles and preferences.
6. **Recommendation System**: 
   - Recommend top-selling products to customers in each segment who haven’t purchased them yet.

---

### **Dataset**
- **Source**: [UCI Machine Learning Repository - Online Retail Dataset](https://archive.ics.uci.edu/dataset/352/online+retail)
- **Description**: The dataset includes details such as Invoice Number, Stock Code, Description, Quantity, Invoice Date, Unit Price, Customer ID, and Country.

---

### **Key Steps**
1. **Exploratory Data Analysis (EDA)**:
   - Analyze data distribution, trends, and patterns.
   - Visualize customer behavior using tools like Matplotlib, Seaborn, and Plotly.

2. **Data Cleaning**:
   - Remove duplicates, handle missing values, and detect outliers using **Isolation Forest**.

3. **Feature Engineering**:
   - Create new features such as Recency, Frequency, and Monetary value (RFM analysis).

4. **Clustering**:
   - Use **Elbow Method** and **Silhouette Analysis** to determine the optimal number of clusters.
   - Compare K-Means and Agglomerative Clustering.

5. **Recommendation System**:
   - Use cluster profiles to recommend products to customers in each group.

---

### **Technologies Used**
- **Programming Languages**: Python
- **Libraries**:
  - Data Analysis: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`, `plotly`
  - Machine Learning: `scikit-learn`, `yellowbrick`
  - Others: `tabulate`, `scipy`

---

### **Results**
- Segmented customers into distinct groups based on purchasing behavior.
- Developed insights into customer preferences for targeted marketing.
- Built a recommendation system to suggest products to customers within each segment.

---

### **Future Work**
- Expand the recommendation system with collaborative filtering.
- Integrate additional datasets to enhance clustering accuracy.
- Deploy the solution as a web application for real-time segmentation and recommendations.

---

### **Contributions**
Contributions are welcome! Feel free to open issues or submit pull requests for suggestions and improvements.
