# Height Prediction Using Decision Tree

## Project Overview
This project demonstrates how machine learning can be used to predict human height based on age using a Decision Tree Regression model.

The project loads a dataset, performs data preprocessing, splits the data into training and testing sets, trains a Decision Tree model, and evaluates the performance using RMSE and R² score.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Project Workflow
1. Load the dataset using Pandas
2. Separate input features (X) and target variable (Y)
3. Split the dataset into training and testing sets
4. Train the model using DecisionTreeRegressor
5. Visualize predictions using Matplotlib
6. Evaluate the model using RMSE and R² score

## Machine Learning Model
The model used in this project is:
Decision Tree Regressor

Decision Trees are supervised learning algorithms used for both classification and regression tasks. In this project, the model learns the relationship between age and height.

## Evaluation Metrics
The model performance is evaluated using:
- Root Mean Squared Error (RMSE)
- R² Score

## Example Prediction
The model predicts height for a given age input.  
Example:
Input Age: 34  
Predicted Height: Model Output

## How to Run the Project

1. Install dependencies
pip install -r requirements.txt

2. Run the Python script
python height_prediction_using_decision_tree.py

## Project Structure

Height-Prediction-Decision-Tree
│
├── height_prediction_using_decision_tree.py
├── dataset.csv
├── requirements.txt
└── README.md

## Author
Nitheesh Kumar
Data Analyst | Data Science Enthusiast
