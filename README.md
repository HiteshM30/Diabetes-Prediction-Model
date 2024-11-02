
# Diabetes Prediction Model

This repository contains a machine learning model designed to predict the likelihood of diabetes in individuals based on various health metrics. The model is trained using a Support Vector Machine (SVM) algorithm, chosen for its effectiveness in classification tasks.



## Overview
Diabetes is a chronic health condition that affects millions of people worldwide. Early prediction of diabetes can aid in timely intervention and better management of the disease. This project utilizes a machine learning approach with a Support Vector Machine (SVM) classifier to predict whether an individual is likely to have diabetes based on certain health indicators.
## Dataset
The model is trained on the PIMA Indian Diabetes Dataset provided by the National Institute of Diabetes and Digestive and Kidney Diseases. This dataset includes medical records for 768 individuals, with 8 features related to health status:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI (Body Mass Index)
- Diabetes Pedigree Function
- Age
Each record is labeled with a binary outcome indicating the presence of diabetes (1) or the absence of it (0).
## Model
The Diabetes Prediction Model uses a Support Vector Machine (SVM) for classification. SVM is suitable for this type of binary classification problem due to its high performance with relatively small datasets and its ability to create decision boundaries for classification.

Key Libraries
- scikit-learn: For implementing the SVM model.
- Pandas & NumPy: For data handling and preprocessing.
## Dependencies
To install the required libraries, run:
```console
pip install -r requirements.txt
```
Primary Libraries Used:

- scikit-learn: Model training and evaluation
- pandas: Data handling and manipulation
- numpy: Storing the input file
## Project Structure
```
├── diabetes.csv        # dataset  
├── main.ipynb          # Jupyter notebook for exploratory data analysis and model training
├── requirements.txt    # Required Python libraries
└── README.md           # Project overview and instructions
```
## Results
After training, the model achieves an accuracy of approximately ```80%``` on the test dataset. Model evaluation metrics can be visualized in the ```main.ipynb``` file.