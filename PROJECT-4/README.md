# Customer Satisfaction Prediction

This project focuses on predicting customer satisfaction based on data from customer support tickets. The entire workflow, from data cleaning and feature engineering to model training and evaluation, is documented in the `Customer_Satisfaction_Prediction_Complete.ipynb` Jupyter Notebook.

## Project Notebook

The analysis is contained within the `Customer_Satisfaction_Prediction_Complete.ipynb` notebook. It builds a machine learning model to identify the key factors that influence customer satisfaction ratings.

### Notebook Details

The notebook follows a systematic approach to solve the prediction problem:

*   **Data Loading and Inspection:**
    *   The `customer_support_tickets.csv` dataset is loaded.
    *   An initial inspection is performed to understand the data structure, data types, and identify missing values.

*   **Data Cleaning and Preprocessing:**
    *   The dataset is filtered to include only "Closed" tickets that have a customer satisfaction rating, as this is our target for prediction.
    *   Unnecessary columns (like IDs, names, and raw descriptions) are dropped.

*   **Feature Engineering:**
    *   Date and time columns are converted to a proper datetime format.
    *   New time-based features are engineered, such as `Response_Delay_Hours` and `Resolution_Time_Hours`, to quantify support performance.

*   **Data Encoding:**
    *   Categorical text-based features (e.g., `Ticket Type`, `Ticket Priority`, `Customer Gender`) are converted into numerical format using label encoding, making them suitable for machine learning models.

*   **Model Training and Comparison:**
    *   The data is split into training and testing sets.
    *   Two classification models, a **Decision Tree** and a **Random Forest**, are trained and compared based on their accuracy. The Random Forest model was selected for its superior performance.

*   **Model Evaluation:**
    *   The final model's performance is evaluated using a **Classification Report** and a **Confusion Matrix** to get detailed insights into its precision, recall, and F1-score for each satisfaction rating.

*   **Feature Importance Analysis:**
    *   The notebook identifies and visualizes the most influential features that contribute to the model's predictions, highlighting the key drivers of customer satisfaction.

