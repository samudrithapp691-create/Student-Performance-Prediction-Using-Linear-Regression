# Student Final Grade Prediction Using Linear Regression

## Overview

This project uses a **Linear Regression** machine learning model to predict a student's final grade (**G3**) based on various academic and behavioral factors. The model is trained using historical student performance data and can estimate the final grade for new students.

## Problem Statement

Educational institutions often need to identify students who may require additional academic support. This project predicts a student's final grade using factors such as study time, previous grades, failures, and absences, helping educators make data-driven decisions.

## Dataset

The dataset contains information about students, including:

* Study Time (`studytime`)
* Number of Past Failures (`failures`)
* Number of Absences (`absences`)
* First Period Grade (`G1`)
* Second Period Grade (`G2`)
* Final Grade (`G3`) – Target Variable

## Features and Target

### Input Features

* `studytime`
* `failures`
* `absences`
* `G1`
* `G2`

### Target Variable

* `G3` (Final Grade)

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Linear Regression

## Project Workflow

1. Import required libraries.
2. Load the dataset.
3. Select features and target variable.
4. Split data into training and testing sets.
5. Train the Linear Regression model.
6. Evaluate model performance using:

   * Mean Squared Error (MSE)
   * R² Score
7. Predict the final grade for a new student.

## Model Evaluation Metrics

### Mean Squared Error (MSE)

Measures the average squared difference between actual and predicted values.

### R² Score

Indicates how well the model explains the variance in the target variable.

### Accuracy

Calculated as:

Accuracy (%) = R² Score × 100

## Example Prediction

Input:

| Feature    | Value |
| ---------- | ----- |
| Study Time | 3     |
| Failures   | 0     |
| Absences   | 5     |
| G1         | 14    |
| G2         | 15    |

Output:

Predicted Final Grade (G3): Model-generated value

## How to Run

1. Clone the repository:

```bash
git clone <repository-url>
```

2. Install required packages:

```bash
pip install pandas scikit-learn
```

3. Place the dataset file (`Maths_converted.csv`) in the project directory.

4. Run the Python script:

```bash
python student_grade_prediction.py
```

## Results

The model predicts student final grades based on academic performance indicators and evaluates prediction quality using MSE and R² Score.

## Future Improvements

* Add more student-related features.
* Compare multiple regression algorithms.
* Implement Polynomial Regression and Random Forest Regression.
* Develop a web-based prediction interface.

## Author

Student Performance Prediction Project using Machine Learning and Linear Regression.

