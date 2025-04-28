# 🛍️ Customer Segmentation Using Clustering Algorithms

## Overview

This project focuses on segmenting customers based on their demographics and purchasing behavior using clustering algorithms like **K-means** and **DBSCAN**.  
Customer segmentation helps businesses to better understand their customers and tailor marketing strategies, offers, and services to different groups.

---

## 📂 Dataset

We used the **Mall Customer Segmentation Dataset**, which contains the following features:
- **CustomerID**: Unique ID for each customer
- **Gender**: Male or Female
- **Age**: Age of the customer
- **Annual Income (k$)**: Customer's annual income in thousands
- **Spending Score (1-100)**: Score assigned based on customer behavior and spending

**Dataset Source**:  
[Kaggle - Mall Customer Segmentation Data](https://www.kaggle.com/datasets/sbhatti/500-premium-customer-dataset)

---

## 🛠️ Project Workflow

1. **Data Collection**  
   Load and explore the customer data.

2. **Data Preprocessing**  
   - Handle missing values
   - Encode categorical features (like Gender)
   - Normalize the features using StandardScaler

3. **Exploratory Data Analysis (EDA)**  
   - Analyze the distributions of features
   - Visualize relationships and correlations

4. **Clustering**  
   - Apply **K-means Clustering**:
     - Use the **Elbow Method** to find the optimal number of clusters.
     - Assign cluster labels to each customer.
   - (Optional) Apply **DBSCAN Clustering**:
     - Detect clusters of arbitrary shape.
     - Identify noise points (outliers).

5. **Model Evaluation**  
   - Evaluate the clustering using **Silhouette Score**.
   - Analyze the characteristics of each segment.

6. **Visualization**  
   - Visualize customer clusters using **PCA** to reduce dimensions to 2D for easy plotting.

7. **Insights & Conclusions**  
   - Understand different customer segments.
   - Provide business recommendations based on segment profiles.

---

## 🧩 Tech Stack

- **Python 3.8+**
- **Libraries**:
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn (for clustering, scaling, PCA)

---

## 📈 Results

After clustering, we successfully segmented customers into distinct groups based on their **age**, **income**, and **spending score**.  
Each cluster represents a customer profile, e.g.:
- **Cluster 1**: Young customers with high spending score
- **Cluster 2**: Older customers with moderate spending
- **Cluster 3**: High-income customers with low spending

---

## 🚀 How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/customer-segmentation.git
   cd customer-segmentation
   ```

2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Python script:
   ```bash
   python customer_segmentation.py
   ```

4. (Optional) Jupyter Notebook:
   ```bash
   jupyter notebook customer_segmentation.ipynb
   ```

---

## 📋 Future Work

- Apply advanced clustering techniques (e.g., Hierarchical Clustering, Gaussian Mixture Models).
- Build a dashboard to monitor customer segments in real-time.
- Predict customer movement across segments over time.

---

## 🤝 Contributing

Pull requests are welcome!  
For major changes, please open an issue first to discuss what you would like to change.

---

## 📧 Contact

If you have any questions or suggestions, feel free to contact:  
**Your Name** — [your.email@example.com](mailto:your.email@example.com)

---

> *Happy Learning and Clustering!* 🚀
