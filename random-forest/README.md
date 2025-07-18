# Random Forest Classifier on Customer Churn Dataset

This notebook implements a **Random Forest Classifier** to predict customer churn using a structured dataset.

## Dataset Description

The dataset used is `customer_churn_dataset-testing-master.csv`, which contains the following types of customer data:

- Demographics (e.g., gender, senior citizen)
- Account information (e.g., tenure, contract type)
- Services subscribed (e.g., phone, internet)
- Financial attributes (e.g., monthly charges, total charges)
- Target variable: `Churn` (Yes/No)

## Objective

To build a machine learning model that can accurately predict if a customer is likely to churn based on their attributes.

## Workflow

1. Loaded and inspected the dataset
2. Handled missing values and converted categorical columns using label encoding
3. Split data into training and testing sets
4. Trained a `RandomForestClassifier`
5. Evaluated the model's performance
6. Visualized key results

## Visualizations

Two visualizations were created to support the model's interpretability:

1. **Feature Importance Plot**  
   Shows which features contributed the most to the classifier’s decision-making.

2. **Confusion Matrix (Bar Chart Format)**  
   Compares actual vs. predicted churn labels to visualize performance.

## Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## How to Run

1. Open the `Random_Forest_Classifier.ipynb` notebook
2. Install required libraries if not already available
3. Run the notebook cells sequentially


