

# Stroke Prediction Model for Imbalanced Healthcare Data

This project focuses on developing a machine learning model for **early stroke prediction** using healthcare data. The model addresses the challenge of class imbalance, which is common in medical datasets, and aims to improve the accuracy of early stroke detection, ultimately aiding in better patient outcomes.

## Key Features:
- **Data Preprocessing**: The pipeline includes advanced techniques for **data cleaning**, **imputation**, and **feature engineering** to ensure high-quality input data.
- **Class Imbalance Handling**: Oversampling techniques were used to address the class imbalance, improving the model’s performance on the minority class (stroke).
- **Random Forest Model**: The project used the **Random Forest** algorithm, which achieved a **recall of 0.89**, outperforming other models like **Logistic Regression** and **KNN**.

## Methodology:
- **Data Cleaning and Imputation**: The raw dataset was cleaned and missing values were handled using imputation methods, ensuring no loss of critical information.
- **Feature Engineering**: The dataset was processed to create informative features that improve model interpretability and performance.
- **Class Imbalance Handling**: **Oversampling techniques** like SMOTE were implemented to balance the dataset, ensuring the model effectively identifies strokes despite their rarity.
- **Model Selection**: **Random Forest** was chosen for its robustness and ability to handle complex, non-linear relationships in the data. It achieved superior performance compared to other models.

## Results:
- **Recall of 0.89**: The Random Forest model achieved an impressive recall score of 0.89, indicating its effectiveness in detecting strokes, especially in the imbalanced dataset.
- **Outperformed Logistic Regression and KNN**: The model surpassed both **Logistic Regression** and **KNN**, showcasing its ability to deal with imbalanced data and make accurate predictions.

## Conclusion:
This project demonstrates the power of advanced machine learning techniques in addressing healthcare challenges. By effectively handling class imbalance and leveraging the Random Forest algorithm, the model offers the potential to improve **early stroke detection** and **patient outcomes**.

