# ⚡ Electricity Bill Prediction using Linear Regression

## 📌 Project Overview
This project uses **Linear Regression**, a supervised machine learning algorithm, to predict household electricity bills based on electricity usage and other related features.

The model is trained using a dataset containing household appliance information, monthly usage hours, tariff rates, city, electricity company, and electricity bill amounts.

## 🎯 Objectives
- Predict electricity bills using machine learning.
- Understand Linear Regression and its working process.
- Evaluate the model using MSE, RMSE, MAE, and R² score.
- Visualize actual and predicted electricity bills.

## 🛠️ Technologies Used
- Python
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook / VS Code

## 📂 Dataset Features
- Appliance information
- City
- Electricity company
- Monthly usage hours
- Tariff rate
- Electricity bill (target variable)

## ⚙️ Workflow
1. Load the dataset.
2. Prepare input features and target values.
3. Convert categorical features into numerical values.
4. Split the dataset into training and testing sets.
5. Train the Linear Regression model.
6. Predict electricity bills.
7. Evaluate model performance.
8. Visualize actual versus predicted values.

## 📊 Evaluation Metrics
- **MSE:** Mean Squared Error
- **RMSE:** Root Mean Squared Error
- **MAE:** Mean Absolute Error
- **R² Score:** Measures how well the model fits the target values.

## 🚀 How to Run
Install the required libraries:

```bash
pip install pandas matplotlib scikit-learn
```

Place the CSV dataset in the project folder and run the Python script.

## 📈 Result
The trained model predicts electricity bill amounts and compares predicted values with actual bills using evaluation metrics and visualization.

## 🔮 Future Improvements
- Add a simple web interface for entering household details.
- Compare Linear Regression with other regression algorithms.
- Test the model on real electricity billing data.

## 👩‍💻 Author
Created as a machine learning practice project to understand Linear Regression and model evaluation.
