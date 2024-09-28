
# Mushroom Classification 

## Overview
This notebook implements a classification model using a mushroom dataset. The goal is to predict whether a mushroom is edible or poisonous based on its various features such as cap shape, color, odor, and more. The classification is performed using a Decision Tree model.

## Steps Included

1. **Data Loading**:
   - The dataset is loaded and examined for initial insights.
   - Categorical variables are encoded into numerical values for model compatibility.

2. **Data Preprocessing**:
   - The dataset is checked for missing values and cleaned.
   - Features are encoded appropriately, transforming all categorical variables into numerical form.

3. **Model Training**:
   - A Decision Tree Classifier is used for classification.
   - The data is split into training and testing sets using an 80/20 split ratio.
   - The Decision Tree model is trained on the training data.

4. **Evaluation**:
   - Predictions are made using the test set.
   - The model is evaluated using the accuracy score and a classification report, which includes precision, recall, and F1-score.
   - The final accuracy achieved by the model is 98%.

## Libraries Used
- `pandas`
- `sklearn`
- `numpy`

## Results
The model achieved high accuracy (98%) in classifying the mushrooms, with precise and balanced results between the two categories: edible and poisonous.

## Conclusion
This notebook demonstrates the effectiveness of a Decision Tree model for classifying categorical data with high accuracy. The mushroom dataset was an excellent example for binary classification tasks.
