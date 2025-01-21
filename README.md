# Loan Prediction Model

## Overview
This repository contains a machine learning project aimed at predicting loan approval status based on various applicant details. The model leverages Python and classification algorithms, along with popular libraries for data preprocessing, visualization, and machine learning.

## Features
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Implementation of classification algorithms (e.g., Logistic Regression)
- Model evaluation and performance metrics

## Technologies Used
- **Programming Language:** Python
- **Libraries:**
  - Data Manipulation: `Pandas`, `NumPy`
  - Visualization: `Matplotlib`, `Seaborn`
  - Machine Learning: `Scikit-learn`

## Dataset
The dataset contains the following key features:
- **Applicant Details:** Gender, Marital Status, Education, Income, etc.
- **Loan Details:** Loan Amount, Loan Term, Credit History, etc.
- **Target Variable:** Loan Status (Approved/Rejected)




   

## Usage
1. **Preprocess Data:**
   - Clean the dataset by handling missing values and encoding categorical variables.

2. **Run EDA:**
   - Use the provided notebooks or scripts to visualize and analyze the data.

3. **Train the Model:**
   - Train the classification model by running:
     ```bash
     python train_model.py
     ```

4. **Evaluate Performance:**
   - Check model accuracy and other metrics using the test dataset.



## Results
- Achieved an accuracy of **85%** using Logistic Regression.
- Key insights from EDA:
  - Credit history significantly influences loan approval.
  - Higher income increases chances of approval.

## Future Improvements
- Implement additional classification algorithms (e.g., Random Forest, XGBoost).
- Optimize hyperparameters using GridSearchCV or RandomizedSearchCV.
- Deploy the model using Flask or FastAPI.

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.


## Contact
For any questions or feedback, please contact:
- **Name:** Subhadip Dey
- **Email:** subhadipdey411@gmail.com
