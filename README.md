# 📊 Student Scores Prediction

## 🎯 Project Overview

This project implements a simple linear regression model to predict student scores based on the number of hours studied. Using the `student_scores.csv` dataset, we explore the relationship between study time and academic performance.

### 🌟 Key Features

- Data visualization of study hours vs. scores
- Implementation of simple linear regression
- Model evaluation and prediction
- Comparison of actual vs. predicted scores


## 📈 Project Steps

1. **Data Loading and Exploration**
   - Load the `student_scores.csv` dataset
   - Display the first few rows of the data

2. **Data Visualization**
   - Create a scatter plot to visualize the relationship between hours studied and scores obtained

3. **Data Preparation**
   - Select feature (hours studied) and target variable (scores obtained)
   - Split the dataset into training (80%) and testing (20%) sets

4. **Model Training**
   - Create and train a simple linear regression model using the training data

5. **Prediction and Evaluation**
   - Use the trained model to predict scores on the test data
   - Plot the regression line on the scatter plot of test data
   - Highlight predicted vs. actual scores on the plot

## 📊 Results

- The project demonstrates a clear positive correlation between hours studied and scores obtained.
- The linear regression model provides a reasonable fit to the data, as visualized by the regression line.
- Predicted scores are compared with actual scores to evaluate the model's performance.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 📌 Future Improvements

- Implement more advanced regression techniques (e.g., polynomial regression)
- Incorporate additional features that might influence student scores
- Perform cross-validation for more robust model evaluation
