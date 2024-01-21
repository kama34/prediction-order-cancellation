<p align="center">
      <img src="https://i.ibb.co/0tnp8Wy/uber-eats-logo-CA3-BA2098-B-seeklogo-com.png">
</p>

<p align="center">
   <img src="https://img.shields.io/badge/Pandas-lavender" alt="Pandas">
   <img src="https://img.shields.io/badge/NumPy-thistle" alt="NumPy">
   <img src="https://img.shields.io/badge/Matplotlib-lightcyan" alt="Matplotlib">
   <img src="https://img.shields.io/badge/ydata_profiling-lavender" alt="ydata_profiling">
   <img src="https://img.shields.io/badge/Logistic_Regression-thistle" alt="LogisticRegression">
   <img src="https://img.shields.io/badge/Random_Forest-lightcyan" alt="RandomForestClassifier">
   <img src="https://img.shields.io/badge/Gradient_Boosting-lavender" alt="GradientBoostingClassifier">
</p>

## About

Food delivery companies and systems has skyrocketed in recent years, driven by various factors. The convenience and ease of ordering food from the comfort of one’s home or office have made food delivery a preferred choice for many consumers. With a desire to optimize operational efficiency, reduce costs, and enhance customer satisfaction, food delivery companies have been leveraging machine learning algorithms to predict order cancellation and to forecast their resources such as active couriers. In this project I used machine learning to predict order cancellation.

## Documentation

### Introduction
This project focuses on analyzing order cancellation data and building machine learning models to predict order status. The dataset includes information such as order status, order items, cost, delivery time, and more. Through data preprocessing, balancing, and training various classification models, the goal is to predict order cancellations accurately.

### Overview
The project involves loading and preprocessing data, handling missing values, outliers, and categorical features. It explores data balancing techniques and employs logistic regression, random forest, and gradient boosting models for classification. Performance metrics such as accuracy, confusion matrix, and classification report are used to evaluate model effectiveness.

### Goals and Objectives
- Analyze order cancellation data.
- Predict order status accurately.
- Compare the performance of logistic regression, random forest, and gradient boosting models.

### Dataset features description
* order_status (text): Order final status, label that indicates if an order was successfully delivered or not (`F` - finished, `C` - cancelled),
* order_create_time (Timestamp) : Time when the order was placed
* total_order_items (int) : total number of items in an order
* tot_unique_items (int) : total number of unique items in an order
* cost(USD) (float): The amount paid by client for the order
* vendor_id (int) : vendor ID
* payment_type (text): Type of payment the client indicated when making an order
* vendor_client_distance (float) : distance between client location and vendor in meters
* estimated_delivery_time (float) : The estimated minutes for delivering order from vendor to client in minutes
* predicted_order_preparation_time (float) : estimated order preparation time by the vendor

### Technologies and Tools
- **Pandas**: Data manipulation and analysis.
- **ydata_profiling**: Profiling the dataset for insights.
- **Scikit-Learn**: Machine learning library for preprocessing and modeling.
- **SMOTE (Synthetic Minority Over-sampling Technique)**: Balancing imbalanced data.
- **Logistic Regression**: Binary classification model.
- **Random Forest Classifier**: Ensemble learning model.
- **Gradient Boosting Classifier**: Boosted ensemble learning model.
- **Accuracy Score**, **Confusion Matrix**, **Classification Report**: Evaluation metrics.

### Data Loading and Preprocessing
The dataset is loaded, profiled, and undergoes preprocessing steps, including handling missing values, sorting by date, dropping unnecessary columns, and removing outliers.

### Data Balancing
SMOTE is applied to balance the data, generating synthetic examples of the minority class (order cancellations).

### Feature Scaling
Data scaling is performed using StandardScaler to ensure neutrality toward feature weighting.

### Logistic Regression Model
Two logistic regression models are trained with L1 and L2 regularization on balanced data. Results are evaluated using accuracy, confusion matrix, and classification report.

### Other Classification Models
Random Forest and Gradient Boosting models are trained and compared with logistic regression results. Evaluation metrics provide insights into model performance.

### Results and Analysis
Both Random Forest and Gradient Boosting models demonstrate high accuracy (about 99%) and perform well on classification tasks. Logistic Regression, in comparison, shows lower accuracy (60%) and poorer performance metrics.

### Conclusion
Random Forest and Gradient Boosting models outperform Logistic Regression in predicting order cancellations. The high accuracy and robust performance metrics make them suitable for this classification task.

## Developers

- Kamyshnikov Dmitrii :
      - [GitHub](https://github.com/kama34)
      - [Email](mailto:kamyshnikovdmitri@yandex.ru)
      - [Telegram](https://t.me/+79101663108)

## License
Project kama34.PredictionOrderCancellation is distributed under the MIT license.
