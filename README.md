# 🏏 IPL Match Winner Predictor

A Machine Learning project that predicts the winner of an IPL cricket match based on team, venue, and toss information.

## 👤 Author
**Isha sree**

## 📌 Overview
This project uses historical IPL match data to train multiple Machine Learning models and automatically selects the best performing one to predict match winners.

## 🎯 Problem Statement
Given two teams, the venue, toss winner, and toss decision — predict which team is likely to win the match.

## 📊 Dataset
- Source: [Kaggle IPL Dataset](https://www.kaggle.com/datasets/ramjidoolla/ipl-data-set)
- 752 matches after data cleaning

## 🔧 Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib

## 🧠 Models Compared
- Logistic Regression
- Decision Tree
- Random Forest
- SVM
- KNN (hyperparameter tuned)
- Naive Bayes

The model automatically compares all algorithms and selects the **best performing one** based on accuracy.

## ⚙️ Workflow
1. Data Cleaning — removed matches with no result
2. Feature Engineering — Label Encoding for categorical features (team, venue, toss)
3. Model Training — trained 6 different ML algorithms
4. Model Selection — automatically picked best performing model
5. Hyperparameter Tuning — optimized K value for KNN
6. Prediction — predicts winner for new/unseen matches

## 📈 Results
Best performing model achieved high accuracy on test data after comparing all 6 algorithms.

## 🚀 How to Run
1. Clone this repository
2. Open `ipl_match_predictor.ipynb` in Jupyter/Colab
3. Run all cells in order
4. Use the saved model (`ipl_predictor_model.pkl`) for new predictions

## 🔮 Future Improvements
- Add more features (player stats, recent form, head-to-head record)
- Deploy as a web app using Streamlit
- Add live match prediction using real-time data

