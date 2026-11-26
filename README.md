#Student Performance Prediction

Mini Project using Linear Regression and Principal Component Analysis (PCA)

##Project Overview

This project uses Python and Machine Learning techniques to predict students' final academic grades based on selected academic and personal study-related factors.

Linear Regression is used to predict the final grade, while Principal Component Analysis (PCA) is applied to reduce the dimensionality of the input data.

##Objectives

- To analyse student academic performance.
- To predict final grades using Linear Regression.
- To apply PCA for dimensionality reduction.
- To evaluate the model using performance metrics.

##Dataset

The project uses the Student Performance Dataset, specifically the Mathematics dataset ("student-mat.csv").

The dataset contains 395 student records and 33 attributes.

Dataset source: "Student Performance Dataset – Kaggle" (https://www.kaggle.com/datasets/dskagglemt/student-performance-data-set)

##Technologies and Tools Used

- Python
- Google Colab
- Pandas
- Matplotlib
- Scikit-learn
- Linear Regression
- Principal Component Analysis (PCA)
- StandardScaler
- GitHub

##Methodology

1. Load the student performance dataset.
2. Select relevant input features and the final grade as the target.
3. Split the data into training and testing sets.
4. Standardize the input features using StandardScaler.
5. Apply PCA for dimensionality reduction.
6. Train the Linear Regression model.
7. Predict student final grades.
8. Evaluate the model using MAE and R² Score.
9. Visualize actual and predicted grades.

##Model Results

- PCA Components: 2
- Mean Absolute Error (MAE): 1.37
- R² Score: 0.76

These results represent the performance of the model on the test dataset.

##Project Structure

Student-Performance-Prediction/

- Student_Performance_Prediction.ipynb
- student-mat.csv
- output.png
- README.md

##How to Run the Project

1. Open the notebook file.
2. Upload "student-mat.csv" when required.
3. Run the notebook cells in sequence.
4. View the model predictions and generated graph.

The notebook can be opened using Google Colab or Jupyter Notebook.

##Conclusion

This project demonstrates how Linear Regression and PCA can be used together to analyse and predict student academic performance. The model provides predictions based on selected student features and evaluates them using standard regression metrics.

##Contributors

- Arzoo Akhtar
- Add your teammate's name here

##References

- Student Performance Dataset – Kaggle
- Scikit-learn Documentation
- Pandas Documentation
- Matplotlib Documentation