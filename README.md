📊 Student Pass/Fail Prediction using Machine Learning
Overview
This project predicts whether a student will pass or fail in mathematics using reading and writing scores. It demonstrates a complete machine learning workflow including data preprocessing, model training, evaluation, and visualization.
Features
Binary classification using Logistic Regression (SGD-based)
Epoch-wise training to observe learning progress
Confusion matrix for performance analysis
Accuracy vs epochs graph for visualization
Dataset
The dataset used is StudentsPerformance.csv, which contains:
Math Score
Reading Score
Writing Score
A new column Pass is created:
1 → Pass (math score > 40)
0 → Fail
Project Structure
Student-ML-Project
model.py
StudentsPerformance.csv
README.md
images
confusion_matrix.png
accuracy_plot.png
Installation
Install required libraries using:
pip install pandas matplotlib seaborn scikit-learn
How to Run
Run the model using:
python model.py
Results
The model achieves high accuracy in predicting passing students
It shows slight bias toward predicting “Pass” due to dataset imbalance
Performance is visualized using confusion matrix and accuracy graph
Future Improvements
Improve prediction for failing students
Add more features for better accuracy
Convert the project into a web application
Try deep learning models
Author
Rugved Choudhari