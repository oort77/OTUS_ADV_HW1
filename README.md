![anomaly_detection_](https://user-images.githubusercontent.com/73858914/149597304-433afb05-5fca-4285-a158-00ff430364ff.png)

**OTUS Machine Learning Advanced**
### **Homework 1** 
### AutoML

*********************

*********************
**Goals:**  
- Apply **anomaly detection** methods to "Credit Card Fraud Detection" dataset
- Carry out basic EDA ☑︎
- Use anomaly percentage, calculated by "Class" variable, as an "expert estimate" of the dataset impurity ☑︎
- Estimate the quality of models with their predictions and "Class" variable, using classificationrt and confusion matrix ☑︎
- Check if anomalies are separated from the rest of data with UMAP/t-sne ☑︎

**Additional goals:**  
- Try outlier detection methods in ATOM library ☑︎
- Look into PyOD possibilities ☑︎
- Apply voting classifier ☑︎

**Dataset:**  

- Credit Card Fraud Detection 
https://www.kaggle.com/mlg-ulb/creditcardfraud#creditcard.csv

**Means:**

All meaningful programming will be done in sklearn and ATOM https://tvdboom.github.io/ATOM/about/.  
Will try PyOD library in a separate notebook.

Sklearn:  
<a href="https://colab.research.google.com/github/oort77/OTUS_PRO_HW3/blob/main/notebooks/otus_pro_hw3_sklearn.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>   
ATOM:  
<a href="https://colab.research.google.com/github/oort77/OTUS_PRO_HW3/blob/main/notebooks/otus_pro_hw3_atom.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>   
PyOD:    
<a href="colab.research.google.com/github/oort77/OTUS_PRO_HW3/blob/main/notebooks/otus_pro_hw3_pyod.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> 

DBSCAN crushes Jupyter kernel on full dataset (~280,000 records). 
Calculations on 10% data with DBSCAN are here:  
<a href="https://colab.research.google.com/github/oort77/OTUS_PRO_HW3/blob/main/notebooks/otus_pro_hw3_sklearn_10pct.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

