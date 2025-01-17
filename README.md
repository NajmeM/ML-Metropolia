
# **Machine Learning Exercises**  

This repository contains four machine learning exercises covering regression, polynomial modeling, and clustering techniques. Each project focuses on real-world data analysis using Python and scikit-learn.  

---

## **1. Linear Regression on Salary Data**  
**Objective**: Predict salaries based on age using linear and polynomial regression.  
**Key Features**:  
- Data visualization and standardization  
- Train-test split and model evaluation  
- Comparison of linear vs. 3rd-order polynomial regression  
- Polynomial regression outperformed linear with **R² ≈ 0.96**  

---

## **2. Polynomial Regression Model Selection**  
**Objective**: Choose the best regression model and evaluate its performance.  
**Key Features**:  
- Validation-based model selection  
- Final model trained on all development data  
- Predicting salaries for specific ages  
- Predictions for extreme ages (5, 89) were unrealistic, highlighting extrapolation limitations  

---

## **3. KMeans Clustering on Lifestyle Data**  
**Objective**: Cluster individuals based on salary, housecare time, height, and weight.  
**Key Features**:  
- Standardization and KMeans clustering (k=2)  
- Cluster centers align with gender-based statistics  
- **Cluster 1**: Lower salary, more housecare (females)  
- **Cluster 0**: Higher salary, less housecare (males)  

---

## **4. Gaussian Mixture Model (GMM) for Clustering**  
**Objective**: Compare soft clustering (GMM) with KMeans for lifestyle data.  
**Key Findings**:  
- GMM provides more flexible clusters but similar results to KMeans  
- Cluster 1 (GMM) aligns with females, Cluster 0 aligns with males  
- Small differences in salary and housecare time between clustered and real data  

---

### **Technologies Used**  
- Python (NumPy, Pandas, Matplotlib)  
- scikit-learn (Regression, Clustering, Standardization)  

These exercises demonstrate core machine learning concepts, model evaluation, and clustering techniques on real-world datasets.