# Hospital-Readmission-Prediction-synthetic-dataset-

This project predicts the likelihood of a patient being readmitted 
to the hospital. The goal was to surface insights that could support 
doctors and nurses in preparing appropriate care.

Models used are 
Logistic Regression, Class Imbalance(using smote), XGBClassifier, XGBoost Hyperparameter Tuning (GridSearchCV)

Dataset
The dataset used in this project was obtained from Kaggle — a synthetic hospital readmission dataset created for educational and machine learning practice purposes.
•	Source: Kaggle
•	Dataset Name: Hospital Readmission Prediction (Synthetic Dataset)
•	Records: 30,000 patients
•	Link: https://www.kaggle.com/datasets/siddharth0935/hospital-readmission-predictionsynthetic-dataset
________________________________________

Pipeline End-To-End:

1.	Exploratory Data Analysis
2.	Features engineering
3.	Data preprocessing
4.	Modelling
5.	 Model Tunning
Model	            Accuracy	Precision	  Recall	       F1
Logistic Regression	60	      0.17	     0.52	        0.25
XGBoost	             64	      0.16	     0.42       	0.23
XGBoost after tunning	0.73	   0.18	     0.32	        0.23



⚠️ Metrics reported for Class 1 (Readmitted) due to class imbalance. greater Accuracy alone is misleading — Recall shows how many real readmissions 


CONCLUSION
This project built a hospital readmission prediction model using structured patient data. While XGBoost achieved 73% accuracy after tuning, the low recall for readmitted patients (0.32) means the model is not yet reliable enough for clinical use.

Future Work
- Apply more advanced imbalance techniques such as cost-sensitive learning
- Engineer additional features from diagnosis and medication history  
- Explore ensemble methods to improve minority class detection
- Use SHAP values to explain individual predictions for clinical staff
- Collect richer real-world data — the synthetic nature of this dataset 
  limits how well the model generalises to actual hospital patients


