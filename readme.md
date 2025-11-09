Spaceship Titanic – Kaggle Competition
Overview
This project is part of the Spaceship Titanic Kaggle competition. The goal is to predict whether a passenger was transported to another dimension during the spaceship accident based on their demographic and travel details.
Objective
Build a machine learning model to classify passengers as Transported (True/False) using the given features.
Dataset
Dataset contains information such as:

HomePlanet, CryoSleep, Cabin, Destination
Age, VIP, RoomService, FoodCourt, ShoppingMall, Spa, VRDeck
Target: Transported

Approach
Data Preprocessing and EDA
Handled missing values and outliers.
Extracted new features from Cabin.
Encoded categorical variables and scaled numeric data.
Model Training and Tuning
Used XGBoost Classifier as the main model.
Hyperparameter tuning performed using RandomizedSearchCV.
Evaluated with accuracy, confusion matrix, and classification report.
Model Evaluation
Achieved around 82% validation accuracy.
XGBoost performed better than baseline models like Logistic Regression and Random Forest.


Tools and Libraries
Python, Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, XGBoost


How to Run

Clone the repository
git clone https://github.com/Pranjali-baviskar/Spaceship_titanic_prediction.git
cd Spaceship_titanic_prediction

Install dependencies
pip install -r requirements.txt

Open and run the notebook Spaceship_Titanic.ipynb.


Author
Pranjali Baviskar
