# Air Travel Satisfaction Prediction

This project aims to predict air travel satisfaction using machine learning techniques. The dataset utilized contains various features related to air travel, such as satisfaction ratings, travel type, and flight distance. A logistic regression model is developed to forecast traveler satisfaction based on factors including age, class, type of travel, and seat comfort.

# Requirements

The dataset can be downloaded from [Kaggle](https://www.kaggle.com/datasets/sjleshrac/airlines-customer-satisfaction).

## Dataset
The dataset, named "Invistico_Airline.csv", comprises the following columns:
- Satisfaction
- Gender
- Customer Type
- Age
- Type of Travel
- Class
- Flight Distance
- Various satisfaction ratings for different aspects of the flight experience

## Data Preprocessing
Preprocessing steps involve:
- Conversion of categorical labels to numerical values
- Consistent renaming of column labels
- Handling missing values (if any)

## Model Building
1. **Logistic Regression**: 
   - An initial logistic regression model is constructed using age and class as predictors, achieving an accuracy score of 0.644.

2. **Model Enhancement**:
   - A more comprehensive logistic regression model is built with additional predictors including type of travel and seat comfort. This model attains an accuracy score of 0.688.
   - Evaluation metrics such as accuracy, precision, recall, and F1-score are computed. The confusion matrix offers insights into false positives and false negatives.

## Visualization
- Line plots depict the relationships between age and average satisfaction, age and average flight distance, and class and average seat comfort.
- A receiver operating characteristic (ROC) curve illustrates the logistic regression model's predictive performance regarding air travel satisfaction.

## Conclusion
The logistic regression model provides valuable insights into the determinants of air travel satisfaction. Further enhancements and feature engineering could potentially improve predictive accuracy.

For detailed code implementation, kindly refer to the provided Python script.
