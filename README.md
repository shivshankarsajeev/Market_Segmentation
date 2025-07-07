# Customer Segmentation Using Machine Learning

**Technologies:** Python, Scikit-learn, Streamlit, Pandas, Matplotlib, Seaborn

## 📌 Project Overview

This project implements a machine learning pipeline for customer segmentation using a credit card dataset (~9,000 customers). The goal is to identify distinct customer profiles to support targeted marketing strategies and business decision-making.

---

## 🧠 Key Features

- **Exploratory Data Analysis (EDA):**  
  Conducted detailed analysis to understand feature distributions, correlations, and outliers.

- **Preprocessing & Dimensionality Reduction:**  
  - Handled missing values, standardized features, and reduced dimensionality using **Principal Component Analysis (PCA)**.

- **Clustering Models:**  
  - Applied multiple unsupervised algorithms:  
    - ✅ K-Means (best performance)  
    - DBSCAN  
    - Agglomerative Clustering  
    - Spectral Clustering  
    - Gaussian Mixture Models  
  - Selected K-Means using the **elbow method** and **silhouette scores**.

- **Cluster Analysis:**  
  - Identified meaningful customer segments with distinct spending and payment behaviors.  
  - Visualized clusters in 2D PCA space.

- **Supervised Learning (Prediction Model):**  
  - Trained a **Decision Tree Classifier** to predict customer segments with **~95% accuracy**.

- **Web App Deployment:**  
  - Built and deployed an interactive **Streamlit app** where users can input features and get **real-time segment predictions**.

---

## 🚀 How to Run

```bash
# 1. Clone the repository
git clone https://github.com/your-username/customer-segmentation-ml.git
cd customer-segmentation-ml

# 2. Install dependencies
pip install -r requirements.txt

# 3. Launch the Streamlit app
streamlit run app.py
