# Prodigy_Ds_03
# Task 03: Decision Tree Classifier – Customer Purchase Prediction

This project was completed as part of the Data Science Internship at **Prodigy Infotech**. The objective of this task is to build a **Decision Tree Classifier** to predict whether a customer will subscribe to a term deposit based on various personal and campaign-related features.

## Dataset

**Source**: [Bank Marketing Dataset – UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)  
The dataset is provided by Prodigy Infotech and originally sourced from a Portuguese banking institution’s direct marketing campaigns.

It includes client demographic information, contact communication details, and outcomes of previous campaigns.

## Features

Some of the important features in the dataset include:

- `age`: Age of the client
- `job`: Type of job
- `marital`: Marital status
- `education`: Level of education
- `default`: Has credit in default?
- `balance`: Average yearly balance
- `housing`: Has a housing loan?
- `loan`: Has a personal loan?
- `contact`: Contact communication type
- `day`, `month`, `duration`, `campaign`, `pdays`, `previous`: Campaign details
- `poutcome`: Outcome of previous marketing campaigns

**Target Variable**:  
- `y`: Indicates whether the client subscribed to a term deposit (`yes` or `no`)

## Steps Performed

1. **Data Preprocessing**  
   - Handled missing values  
   - Encoded categorical variables using LabelEncoder and OneHotEncoder  

2. **Train-Test Split**  
   - Split data into training and testing sets for model evaluation  

3. **Model Building**  
   - Used a Decision Tree Classifier from `scikit-learn`  
   - Tuned using default parameters for interpretability  

4. **Evaluation**  
   - Accuracy Score  
   - Confusion Matrix  
   - Classification Report  

5. **Visualization**  
   - Visualized the decision tree to understand how decisions are made  

## Tools and Libraries Used

- Python (Jupyter Notebook)
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Conclusion

The Decision Tree model offers a simple and interpretable way to predict customer behavior regarding term deposit subscriptions. While it may not always offer the highest accuracy compared to more complex models, its transparency makes it highly valuable in real-world applications.


