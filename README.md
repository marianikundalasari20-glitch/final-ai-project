# Student Academic Performance Prediction using Machine Learning

## 1. Project Description
This project aims to predict students’ academic performance using machine learning techniques.
The task is formulated as a binary classification problem to determine whether a student will
pass or fail based on academic, demographic, and social features.

Multiple supervised learning models are implemented and compared to evaluate their performance.

---

## 2. Dataset
This project uses the Student Performance Dataset (Mathematics) from the UCI Machine Learning Repository.

- Dataset file: student-mat.csv
- Number of instances: 395 students
- Number of features: 33 attributes
- Target variable: Final academic performance (Pass / Fail), derived from the final grade (G3)

The dataset includes features such as:
- Study time
- Absences
- Parental education
- Previous grades (G1, G2)

NOTE:
The dataset file is not uploaded to GitHub.
Please download it manually from the UCI Machine Learning Repository and place it in the data/ folder
before running the notebook.

---

## 3. Environment Setup and Requirements
- Python 3.x
- Required libraries are listed in requirements.txt

Install dependencies using:
pip install -r requirements.txt

---

## 4. Instructions to Reproduce Results
1. Clone or download this GitHub repository
2. Open a terminal or command prompt
3. Navigate to the project directory
4. Start Jupyter Notebook using:
   jupyter notebook
5. Open the file new_project.ipynb
6. Run all cells from top to bottom

All preprocessing, training, and evaluation steps are included in the notebook.

---

## 5. Steps to Train Your Own Model
The notebook follows these main steps:
- Data loading and preprocessing
- Feature selection
- Model training using:
  * Logistic Regression
  * Support Vector Machine (Linear Kernel)
  * Random Forest
  * K-Nearest Neighbors (KNN)
- Model evaluation using accuracy, confusion matrix, and classification report

Model parameters can be modified directly in the notebook to retrain the models.

---

## 6. Results Summary
Four machine learning models were trained and evaluated using classification accuracy:

- KNN (K = 7): 93.67%
- Logistic Regression: 92.41%
- SVM (Linear Kernel): 91.14%
- Random Forest: 91.14%

The best performing model is K-Nearest Neighbors (K = 7) with an accuracy of 93.67%.

Key findings:
- Previous academic grades (G1 and G2) are the strongest predictors of final performance
- High absences and previous failures increase the risk of failing
- Simple machine learning models can achieve strong performance on structured educational data

---

## 7. Notes and Limitations
- The dataset size is relatively small
- Results may not generalize to different education systems
- Future work may include feature engineering or advanced models

---

## 8. Dataset Reference
Yağcı, M. (2022).
Educational Data Mining: Prediction of Students’ Academic Performance Using Machine Learning Algorithms.
Education and Information Technologies.

