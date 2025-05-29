# 🧠 ANN for Clustering Customer Segments

> **Course**: DA221 — *Introduction to AI*  
> **Team**: *The Upside Down*

## 👥 Team Members

- M. Abhiram (230150015)  
- K. Ashmita (230150014)  
- B. Cherish (230150007)

---

## 📌 Project Description

This project focuses on **clustering customers** based on their **purchasing behavior** in a shopping mall.  
Instead of using traditional K-Means, we employed an **Artificial Neural Network (ANN)** for clustering.  

> We've designed a custom **MMJ-K-Means Loss** function to transform this into a **supervised learning** approach, unlike the standard competitive learning models.

---

## ⚙️ Implementation Steps

1. Load and preprocess the dataset
2. Perform Exploratory Data Analysis (EDA) using Matplotlib and Seaborn
3. Normalize numerical features using `StandardScaler` (Scikit-learn)
4. Design an **Autoencoder (PyTorch)** for dimensionality reduction
5. Extract **Latent Space** from the bottleneck layer
6. Design an **ANN for Clustering** (PyTorch)
7. Define and implement the **MMJ-K-Means Loss** for soft clustering
8. Train the ANN and visualize clusters
9. Compute the **Silhouette Coefficient** as an internal clustering evaluation index
10. Interpret clusters based on **marketability and targeted marketing potential**

---

## 🧰 Libraries Used

- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`
- `torch` (PyTorch)

---

## 📂 Dataset Information

- **File**: `Mall_Customers.csv`
- **Features**:
  - `CustomerID` *(redundant)*
  - `Gender` *(one-hot encoded)*
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1-100)`
- **Samples**: 200 customer data points

📌 **Note**: Ensure `Mall_Customers.csv` is present in the same directory as the notebook.

---

## 💻 How to Run

1. Open the Jupyter Notebook file: `ANN_Clustering_Code.ipynb`
2. Confirm that `Mall_Customers.csv` is in the same directory
3. Run all cells in order

### 🧾 What You’ll See:
- Data Preprocessing and EDA
- Autoencoder Latent Space visualization
- ANN-based Clustering output
- Cluster evaluation using Silhouette Score
- Marketing insights based on cluster segments

---

## 📦 Installation

Install all required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn torch
