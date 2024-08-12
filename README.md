## Heart Disease Risk Prediction

This project focuses on predicting the risk of heart disease using a neural network model. The dataset used contains various health metrics and demographic data, and the goal is to create a predictive model that can accurately assess the risk of heart disease in patients.

## Project Overview

Heart disease is a leading cause of death worldwide, and early prediction can significantly improve treatment outcomes. In this project, we utilize a neural network implemented with Keras to predict the likelihood of heart disease based on a range of features like age, sex, blood pressure, cholesterol levels, and more.

## Libraries Used

The following Python libraries were used in this project:

- **Python 3.8.5**: The core programming language used for this project.
- **Pandas 1.2.0**: For data manipulation and analysis.
- **NumPy 1.19.2**: For numerical computations and handling arrays.
- **Scikit-learn 0.24.0**: Used for data preprocessing, including train-test split and scaling.
- **Matplotlib 3.3.3**: For data visualization and plotting graphs.
- **Keras 2.4.3**: For building and training the neural network model.

## Dataset

- **Source**: The dataset is loaded from a CSV file named `heart.csv`.
- **Shape**: The dataset contains 303 examples and 14 features.
- **Features**: The dataset includes demographic and health-related metrics such as age, sex, chest pain type (cp), resting blood pressure (trestbps), cholesterol (chol), and target variable indicating the presence or absence of heart disease.

## Data Preprocessing

- Removed missing data and cleaned the dataset to ensure accuracy in predictions.
- Features were scaled and normalized to improve model performance.
- The dataset was split into training and testing sets to evaluate model performance effectively.


## Model Development

- A neural network was developed using Keras to predict heart disease risk.
- The model was trained on the processed dataset, with the architecture optimized for accuracy.
- Various hyperparameters were adjusted, including the number of layers, neurons, activation functions, and optimization algorithms - Produced an accuracy of 81.97%

## Model Evaluation

- The model's performance was evaluated on the test set, with accuracy, precision, recall, and F1-score being the primary metrics.
- Visualizations were created to assess the model's performance, including loss and accuracy curves.

## Conclusion

The neural network model provided an accurate prediction of heart disease risk, offering a potential tool for healthcare professionals to identify high-risk patients early.
