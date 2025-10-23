# Salary-Prediction-using-Random-Forest-Regression


Random Forest Regression - Salary Prediction
This project implements a Random Forest Regression model to predict salaries based on years of experience. The model is trained on a dataset containing salary information and corresponding years of experience, and it demonstrates high predictive accuracy.

📁 Project Structure
text
random_forest_regression/
├── random_forest_regression.ipynb  # Jupyter notebook with complete implementation
├── salary_data.csv                 # Dataset used for training and testing
└── README.md                       # Project documentation (this file)
🚀 Features
Data Preprocessing: Import and prepare the dataset for training

Random Forest Model: Implementation using scikit-learn's RandomForestRegressor

Model Evaluation: Performance assessment using R² score

Visualization: Plotting actual vs predicted salaries with smooth regression curves

High Accuracy: Achieved R² score of 0.9907 (99.07% accuracy)

📊 Dataset
The dataset salary_data.csv contains:

YearsExperience: Independent variable (features)

Salary: Dependent variable (target)

Dataset Statistics:

30 data points

Experience range: 1.1 to 10.5 years

Salary range: $37,731 to $122,391

🛠️ Implementation Details
Libraries Used
numpy - Numerical computations

pandas - Data manipulation

matplotlib - Data visualization

scikit-learn - Machine learning algorithms

Model Configuration
python
RandomForestRegressor(n_estimators=10, random_state=0)
Key Steps
Data Loading: Import dataset and split into features (X) and target (y)

Model Training: Fit Random Forest regressor on the entire dataset

Prediction: Generate salary predictions

Evaluation: Calculate R² score to measure model performance

Visualization: Create scatter plots with regression lines

📈 Results
R² Score: 0.9907 (Excellent fit)

The model captures the non-linear relationship between experience and salary effectively

Visualizations show smooth regression curves that fit the data well

🎯 Usage
Clone the repository

Ensure required libraries are installed:

bash
pip install numpy pandas matplotlib scikit-learn jupyter
Open random_forest_regression.ipynb in Jupyter Notebook

Run all cells to reproduce the analysis

📋 Code Highlights
Complete implementation of Random Forest Regression

Data visualization with actual vs predicted values

Model performance evaluation metrics

Smooth curve plotting for better visualization
