🧬**E. coli Carbapenem Resistance Prediction using Machine Learning**

📂 **Dataset**

This project utilized the Bacterial and Viral Bioinformatics Resource Center (BVBRC) dataset containing phenotypic and metadata information associated with carbapenem resistance in Escherichia coli isolates. The dataset included resistance profiles for major carbapenem antibiotics such as imipenem, meropenem, ertapenem, and doripenem, along with additional genomic and laboratory-associated metadata.

**🎯Overview**

This project focuses on the classification of carbapenem antibiotic resistance into:

✔️Resistant

✔️Susceptible

✔️Intermediate

using phenotypic and genomic metadata obtained from the BVBRC dataset

**📌Workflow**

✅Data preprocessing

✅Feature engineering

✅Train–test splitting

✅Class imbalance fitting using SMOTE

✅Training multiple ML algorithms

✅Performance evaluation using statistical metrices

✅ROC-AUC analysis

✅Confusion matrix visualization

✅SHAP explainability analysis

**⚙️Machine Learning Pipeline:**

**✅Data Preprocessing**

The preprocessing workflow includes:

✔️Removal of irrelevant columns

✔️Missing value handling

✔️Encoding categorical variables

✔️Feature selection

✔️Train–test splitting

✔️Dataset balancing using SMOTE

 **🤖Machine Learning Models Used**

✔️Random Forest	Ensemble tree-based classifier

✔️Support Vector Machine (SVM)	

✔️K-Nearest Neighbors (KNN)

✔️Logistic Regression

✔️Gradient Boosting

✔️XG Boost

✔️AdaBoost

 **📈Visualization and Explainability**

The project includes several advanced visualization and explainability analyses:

**✅ROC-AUC Curve**

Multi-class ROC analysis for:

✔️Resistant

✔️Susceptible

✔️Intermediate

**✅Confusion Matrix**

Detailed confusion matrix interpretation with normalized values and publication-quality visualization.

✅ SHAP (SHapley Additive exPlanations)

Explainable AI analysis to identify the most important features contributing to resistance prediction.

**✅SHAP analysis includes**:

✔️Global feature importance

✔️Class-wise SHAP plots

✔️Feature contribution analysis
