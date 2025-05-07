# Loan Qualification Prediction

This project aims to automate the process of evaluating loan eligibility based on account holder information. The dataset includes various features such as gender, marital status, dependents, education, income, and more. The goal is to preprocess the data, train multiple models, and evaluate their performance for predicting loan approval.



##  Project Structure

loan-qualification-prediction/
├── data/                     # Raw dataset (.csv)
├── notebooks/                # Jupyter notebook(s) for data analysis and model building
│   └── loan_qualification.ipynb
└── README.md                 # Project description and instructions



##  Data Preparation

The project involves several key data preprocessing steps:

1. **Read Data**: Loading the dataset into the environment.
2. **Manage Null Data**: Identifying and handling missing data.
3. **Feature Engineering**: Transforming raw features into more meaningful features for model training.
4. **Train and Test Split**: Dividing the data into training and testing sets to evaluate model performance.



##  Model Creation

After preprocessing the data, various machine learning models were trained, including but not limited to:

- Logistic Regression
- Decision Trees
- Random Forest
- Support Vector Machines

These models were evaluated based on their performance in predicting loan approval status.


##  Model Evaluation

The models are evaluated based on the following:

- Accuracy: How well the model performs overall.
- Precision & Recall: How well the model identifies positive cases (approved loans).
- F1 Score: A balanced evaluation between precision and recall.
- Confusion Matrix: To see the false positives and false negatives.



##  Tools & Technologies

- TensorFlow/Keras for neural network models
- Imbalanced-learn (imblearn) for oversampling techniques
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn



