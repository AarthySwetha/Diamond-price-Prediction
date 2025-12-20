💎 Gemstone Price Prediction using Linear Regression
📌 Project Overview

This project performs Exploratory Data Analysis (EDA) and price prediction on a gemstone dataset using Linear Regression. The objective is to understand feature relationships affecting gemstone prices and build a regression model to predict prices based on both numerical and categorical attributes.

The workflow is implemented without using pipelines, focusing on manual preprocessing steps for learning clarity.

📂 Dataset

File: gemstone.csv

Target Variable: price

Features:

Numerical attributes (e.g., carat, depth, table, dimensions)

Categorical attributes (e.g., cut, color, clarity)

⚙️ Technologies & Libraries Used

Python

Pandas – data handling

NumPy – numerical computation

Matplotlib & Seaborn – visualization

Scikit-learn – model building and evaluation

🔍 Exploratory Data Analysis (EDA)

The following EDA steps are performed:

Display dataset structure using head(), info(), and describe()

Check for missing values

Correlation heatmap for numerical features

Price distribution visualization using histograms

🧠 Data Preprocessing

Target (price) separated from features

Categorical features identified and One-Hot Encoded

Numerical features retained as-is

Encoded categorical and numerical features combined manually using NumPy

Train-test split performed (80% training, 20% testing)

📈 Model Building

Algorithm: Linear Regression

Model trained on processed training data

Predictions generated on test data

📊 Model Evaluation

The model is evaluated using:

RMSE (Root Mean Squared Error)

R² Score

These metrics help assess prediction accuracy and goodness of fit.

▶️ How to Run the Project

Clone the repository:

git clone https://github.com/AarthySwetha/Diamond-price-Prediction/blob/main/Diamond_price_prediction.ipynb


Navigate to the project folder:

cd gemstone-price-prediction


Ensure gemstone.csv is present in the same directory

Run the notebook or script in Python / Google Colab

📌 Key Learnings

Manual feature encoding without pipelines

Practical EDA for regression problems

Handling mixed numerical and categorical data

Linear regression evaluation techniques

🚀 Future Enhancements

Feature scaling and normalization

Try advanced regression models (Ridge, Lasso, Random Forest)

Hyperparameter tuning

Cross-validation

Model deployment using Flask or FastAPI

👩‍💻 Author

Aarthy Swetha M

