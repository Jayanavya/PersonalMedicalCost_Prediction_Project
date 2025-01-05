# PersonalMedicalCost_Prediction_Project

This project implements a machine learning model to predict personal medical costs based on various features such as age, BMI, and smoking habits. Quantile regression is used to estimate costs at different quantiles, providing a more detailed understanding of cost distribution. 
---

## Features

- Visualizes cost prediction intervals. 
- Highlights key cost-driving factors.
- Uses machine learning models (Linear Regression, Decision Trees, Random Forest).
- Employs quantile regression to capture variability in costs.  
- Includes data cleaning and visualizations.

## Setup

1. Clone the repository:
   bash
   git clone https://github.com/Jayanavya/PersonalMedicalCost_Prediction_Project.git
   
2. Navigate to the folder:
   bash
   cd PersonalMedicalCost_Prediction_Project
   
3. Install dependencies:
   bash
   pip install -r requirements.txt
   
## Usage

1. Add your dataset to data/.
2. Prepare data:
   bash
   python preprocess.py
   
3. Train the model:
   bash
   python train.py
   
4. Evaluate the model:
   bash
   python evaluate.py
   
5. Predict costs:
   bash
   python predict.py --input <data_file>
   
## Data Overview

- *Age*: Age of the person.
- *Sex*: Gender.
- *BMI*: Body Mass Index.
- *Children*: Number of dependents.
- *Smoker*: Smoking status (Yes/No).
- *Region*: Residential region.
- *Charges*: Insurance cost (target variable).

## Results

Performance metrics:
- *MAE:* [Value]
- *RMSE:* [Value]
- *R²:* [Value]

Find detailed results in the results/ folder.



Thank you for exploring this project!
