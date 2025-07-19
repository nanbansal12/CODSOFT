# 🚢 Titanic Survival Prediction - Data Science Project

This project uses the famous Titanic dataset to predict passenger survival using machine learning. We build and evaluate a Logistic Regression model using Python and key data science libraries.

## 📁 Project Structure
## 📊 Dataset

- *Source*: [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/data)
- *Description*: Dataset contains details like passenger class, age, gender, fare, and survival status.

## 🛠 Tools & Libraries Used

- Python (Jupyter Notebook)
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn (optional, for visualization)

## 🧹 Data Preprocessing

- Handled missing values (Age and Fare using median)
- Dropped non-useful columns (Sex, Embarked)
- Converted categorical features using pd.get_dummies()
- Split the data into training and test sets

## 🤖 Model

- *Algorithm*: Logistic Regression
- *Evaluation Metrics*:
  - Accuracy Score
  - Classification Report (Precision, Recall, F1)

## 📈 Results

- Achieved an accuracy of around 0.7318435754189944
- Model provides basic prediction on whether a passenger would survive or not

## 📌 How to Run

1. Clone this repository
2. Open titanic_project.ipynb in Jupyter Notebook
3. Run all cells to train and test the model

