
# SVM Housing Price Prediction

## 📌 Project Overview
This project uses Support Vector Regression (SVR), a machine learning algorithm, to predict house prices based on housing features.

## 🎯 Objective
To build a machine learning model that predicts house prices using the available housing dataset.

## 🛠️ Technologies Used
- Python
- Pandas
- Scikit-learn

## 📂 Dataset
The project uses `Housing.csv`, which contains housing-related features and a target column named `price`.

Categorical features are converted into numerical values using one-hot encoding.

## ⚙️ Algorithm
**Support Vector Regression (SVR)**

SVR is the regression version of Support Vector Machines. It is used to predict continuous numerical values such as house prices.

## 🔄 Methodology
1. Load the housing dataset using Pandas.
2. Convert categorical features into numerical values.
3. Separate input features (`X`) and target variable (`y`).
4. Split the dataset into training and testing sets.
5. Standardize the input features using `StandardScaler`.
6. Train the SVR model.
7. Predict house prices on the test dataset.
8. Evaluate the model using MAE and R² score.

## 📊 Performance Metrics
- **Mean Absolute Error (MAE):** Measures the average absolute difference between actual and predicted prices. Lower values are better.
- **R² Score:** Measures how well the model explains variations in house prices. Values closer to 1 generally indicate a better fit.

Actual metric values depend on the dataset and model results.

## ▶️ How to Run the Project

### 1. Install the required libraries
```bash
pip install pandas scikit-learn
```

### 2. Place the files in the same folder
- `svm1.py`
- `Housing.csv`

### 3. Run the program
```bash
python svm1.py
```

## ✅ Expected Output
The program displays:
- MAE (Mean Absolute Error)
- R² Score

## 🚀 Future Improvements
- Compare SVR with Linear Regression and Random Forest Regression.
- Tune model hyperparameters to improve prediction performance.
- Visualize actual versus predicted house prices.

## 👩‍💻 Author
Prantika Gharui
