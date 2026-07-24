# 🎬 Movie Rating Prediction using Machine Learning

## Project Overview

This project aims to predict movie ratings using Machine Learning techniques. The model analyzes different movie-related features such as genre, director, actors, year, duration, and votes to estimate the rating of a movie.

The project follows a complete Machine Learning workflow, including data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and prediction.

---

## Objective

The main objective of this project is to build a regression model that can accurately predict movie ratings based on available movie information.

---

## Dataset

Dataset Used: IMDb Movies India Dataset

The dataset contains information about Indian movies, including:

- Movie Name
- Year of Release
- Duration
- Genre
- Director
- Actors
- Votes
- Rating

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Joblib

---

## Machine Learning Model

### Random Forest Regressor

A Random Forest Regression model was implemented to predict movie ratings.

The model combines multiple decision trees to improve prediction accuracy and reduce overfitting.

---

## Project Workflow

- Importing Required Libraries
- Loading the IMDb Dataset
- Exploratory Data Analysis (EDA)
- Understanding Dataset Structure
- Handling Missing Values
- Removing Duplicate Records
- Data Preprocessing
- Feature Selection
- Encoding Categorical Features
- Splitting Data into Training and Testing Sets
- Model Training
- Model Evaluation
- Making Predictions

---

## Data Preprocessing

The following preprocessing techniques were applied:

- Removed duplicate entries
- Cleaned column names
- Handled missing values
- Filled categorical values using mode
- Filled numerical values using median
- Applied One-Hot Encoding for categorical features

---

## Model Evaluation

The model was evaluated using the following regression metrics:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## Results

The trained Random Forest Regression model successfully predicts movie ratings by learning patterns from movie features.

The model performance was analyzed by comparing actual ratings with predicted ratings.

---

## Project Structure
Movie-Rating-Prediction/
│
├── Movie_Rating_Prediction.ipynb
├── IMDb Movies India.csv
├── movie_rating_prediction_model.pkl
├── requirements.txt
└── README.md

---

## How to Run the Project

1. Clone the repository

2. Install required dependencies

3. Open the Jupyter Notebook

4. Run all the cells to train the model and generate predictions.

---

## Future Improvements

- Implement advanced algorithms like XGBoost and Gradient Boosting
- Perform hyperparameter tuning for better accuracy
- Add more movie features
- Deploy the model using Streamlit or Flask
- Create a user-friendly movie rating prediction application

---

## Author

**Sharrafa S**

---

If you find this project useful, please consider giving it a ⭐ star on GitHub. Your support encourages me to build and share more Machine Learning and Data Science projects!
