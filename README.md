![anomaly_detection_](https://user-images.githubusercontent.com/73858914/149597304-433afb05-5fca-4285-a158-00ff430364ff.png)

**OTUS Machine Learning Advanced**
### **Homework 1** 
### AutoML
*******************  
**Goals:**  

AutoML: try out automatic feature generation/selection and modelling:  
- Compare AutoML performance in ATOM library (provides TPOT wrapper)   
https://tvdboom.github.io/ATOM/about/  
with baseline and two out of the box models.
- Compare AutoML performance in AutoML mljar-supervised library  
https://github.com/mljar/mljar-supervised  
with two out of the box models.
In addition, will try ensembling of autoML models.

**Means:**  

AutoML tasks will be given to ATOM and mljar-supervised respectively.
All preprocessing and pipelines management will be done in ATOM.

**Dataset:**  

- Richter's Predictor: Modeling Earthquake Damage  
https://www.drivendata.org/competitions/57/nepal-earthquake/data/

**Choice of models**  

- Random Forest and CatBoost classifiers will compete with AutoML solution.
LogisticRegression is added as a baseline in ATOM case.

**Methodology:**  

- OOB models' hyperparameters will be tuned with BO primarily to get some CV statistics and to level up the competition ground.  
- Weighted F1 score will be used as the main performance metrics following  suggestion of the  
competition organizers. Other metrics are collected where possible.

ATOM autoML:

mljar-supervised AutoML:  

<a href="https://colab.research.google.com/github/oort77/OTUS_ADV_HW1/blob/main/notebooks/otus_adv_hw1_automl_mljar.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
