# Customer Churn Prediction
## Project Overview
Customer churn prediction is a vital aspect for businesses as it helps in identifying customers who are likely to leave the service. By predicting churn, businesses can take proactive steps to retain customers and improve their services.
## Dataset
The dataset used in this project is the Telco Customer Churn dataset, which includes information about customer demographics, account information, and services used. The dataset is publicly available and can be found on Kaggle.
## Features
- `gender`: Gender of the customer
- `SeniorCitizen`: Whether the customer is a senior citizen or not (1, 0)
- `Partner`: Whether the customer has a partner or not (Yes, No)
- `Dependents`: Whether the customer has dependents or not (Yes, No)
- `tenure`: Number of months the customer has stayed with the company
- `PhoneService`: Whether the customer has phone service or not (Yes, No)
- `MultipleLines`: Whether the customer has multiple lines or not (Yes, No, No phone service)
- `InternetService`: Customer’s internet service provider (DSL, Fiber optic, No)
- `OnlineSecurity`: Whether the customer has online security or not (Yes, No, No internet service)
- `OnlineBackup`: Whether the customer has online backup or not (Yes, No, No internet service)
- `DeviceProtection`: Whether the customer has device protection or not (Yes, No, No internet service)
- `TechSupport`: Whether the customer has tech support or not (Yes, No, No internet service)
- `StreamingTV`: Whether the customer has streaming TV or not (Yes, No, No internet service)
- `StreamingMovies`: Whether the customer has streaming movies or not (Yes, No, No internet service)
- `Contract`: The contract term of the customer (Month-to-month, One year, Two year)
- `PaperlessBilling`: Whether the customer has paperless billing or not (Yes, No)
- `PaymentMethod`: The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))
- `MonthlyCharges`: The amount charged to the customer monthly
- `TotalCharges`: The total amount charged to the customer
- `Churn`: Whether the customer churned or not (Yes, No)
## Data Preprocessing
- **Handling Missing Values**: Replaced missing values in the `TotalCharges` column with the median.
- **Encoding Categorical Variables**: Converted categorical variables to numerical values using Label Encoding.
- **Feature Scaling**: Standardized the feature variables using StandardScaler.
## Model Building
The model used for this project is an Artificial Neural Network (ANN) built using TensorFlow and Keras. The ANN architecture includes:
- Input layer with 64 neurons and ReLU activation
- Hidden layers with 32 and 16 neurons, each with ReLU activation
- Dropout layers to prevent overfitting
- Output layer with 1 neuron and sigmoid activation
## Results
The model was evaluated on test data and achieved an accuracy of 79%.
## Conclusion
While the model achieved a reasonable accuracy, there is room for improvement. Future work can include hyperparameter tuning, trying different machine learning models, and incorporating more advanced techniques to further improve the accuracy.
