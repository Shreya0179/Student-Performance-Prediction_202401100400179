# Student-Performance-Prediction_202401100400179
Student Performance Prediction

This project aims to predict student exam scores based on study hours and other factors such as attendance, previous scores, and family support. The model uses Linear Regression to make predictions and evaluates performance using Mean Absolute Error (MAE) and R-squared.


Features

Study Hours : Number of hours the student has studied.
Attendance : Percentage of attendance.
Previous Scores : The student's previous exam scores.
Family Support : A scale from 1-10, representing the level of family support.
Exam Scores : The target variable that the model aims to predict.


Tools and Libraries

Python 3.x
Pandas : Data manipulation and analysis.
Numpy : Numerical operations.
Matplotlib : Data visualization.
Scikit-learn : Machine learning library for model building and evaluation.


 Running the Code
 
•	Copy and paste the code into a Google Colab notebook and run it. You can find the full code in the student_performance_prediction.py file.
•	The code will train a Linear Regression model using the provided dataset and evaluate it.


 Understand the Visualizations
 
•	The code generates scatter plots to visualize the relationships between the independent variables (study hours, attendance, etc.) and exam scores.
•	This helps understand how each factor contributes to the prediction of exam scores.


 Model Evaluation
 
•	After training the model, the performance is evaluated using two metrics: 
o	Mean Absolute Error (MAE): Measures the average error in predictions.
o	R-squared: Measures how well the model fits the data (closer to 1 is better).


Code Overview

The code follows these basic steps:
1.	Dataset Creation and Loading
o	A simple dataset is created with sample data. Replace this with your own data if needed.
2.	Data Preprocessing
o	Splits the dataset into features (X) and target variable (y).
o	Splits data into training and testing sets (80% training, 20% testing).
3.	Model Training
o	A Linear Regression model is trained on the dataset.
4.	Evaluation
 The trained model is evaluated using Mean Absolute Error (MAE) and R-squared.
5.	Visualization
Scatter plots show the relationship between features (study hours, attendance, etc.) and the target variable (exam scores).


Model Performance:

Mean Absolute Error: 3.52
R-squared: 0.94


Visualizations:

•	Study Hours vs Exam Scores
•	Attendance vs Exam Scores
•	Previous Scores vs Exam Scores
•	Family Support vs Exam Score


Conclusion

•	This model is a simple introduction to predicting student performance using basic features like study hours and attendance. You can expand this project by adding more features, experimenting with other models, or fine-tuning the existing model for better performance.
Acknowledgements
•	Scikit-learn for the Linear Regression model and other machine learning tools.
•	Matplotlib for visualizations.
•	Pandas for easy data manipulation.
