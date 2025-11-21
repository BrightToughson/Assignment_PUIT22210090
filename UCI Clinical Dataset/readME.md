
# Breast Cancer Coimbra Dataset Analysis and Prediction

This markdown file accompanies the Jupyter notebook for **Breast Cancer Coimbra Dataset Analysis**. It includes the process of exploring the dataset, training a machine learning model, and making recommendations based on predictions.

## Step 1: Load and Inspect Data

We first load the dataset and inspect the first few rows, data types, and basic statistics to understand the structure of the data. We also check for any missing values.

### Dataset Columns:
- **Age**: The age of the patient.
- **BMI**: The body mass index of the patient.
- **Glucose**: The glucose level in the patient's blood.
- **Insulin**: Insulin levels in the blood.
- **HOMA**: Homeostasis model assessment for insulin resistance.
- **Leptin**: A hormone related to fat metabolism.
- **Adiponectin**: A hormone related to the immune system.
- **Resistin**: Another hormone involved in insulin resistance.
- **MCP.1**: A protein related to inflammation.
- **Classification**: Target variable (1 = cancer, 0 = no cancer).

## Step 2: Data Cleaning

We check for missing values in the dataset and perform necessary data cleaning. This step ensures the dataset is ready for model training.

## Step 3: Visualize Data

Histograms and correlation heatmaps are plotted to visualize the distribution of features and understand their relationships with the target variable.

## Step 4: Correlation Matrix

A heatmap is used to visualize the correlation between different features. This step helps to identify which features are most influential in predicting the classification.

## Step 5: Train-Test Split

The dataset is split into training, validation, and testing sets (70% training, 15% validation, 15% testing) to prepare for model training.

## Step 6: Train Logistic Regression Model

A **Logistic Regression** model is trained using the training data to predict whether a patient has cancer (classification 1) or not (classification 0). The model's performance is evaluated using the test set, and key metrics like accuracy, classification report, and confusion matrix are generated.

## Step 7: Make Recommendations Based on Predictions

Once the model is trained, it is used to make predictions for new patients. Based on the model's output, recommendations are generated:
- **If the model predicts cancer** (1), the recommendation is to undergo further diagnostic tests.
- **If the model predicts no cancer** (0), the recommendation is to continue regular monitoring.

### Example:
A new patient's features are input into the model, and based on the predicted classification, a recommendation is generated.

## Conclusion

This notebook provides a simple yet comprehensive analysis of the Breast Cancer Coimbra dataset. It includes exploratory data analysis, model building, and practical recommendations based on predictive outcomes.
