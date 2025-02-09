# 📚 Classification with an Academic Success 🎓

## Introduction
Academic success is a key factor in a student's educational journey. Predicting student performance can help educators identify at-risk students early and take necessary actions to improve outcomes. This project uses machine learning techniques to analyze student data and predict their academic success based on various factors like demographics, previous academic performance, and socioeconomic conditions.

## 🎯 Aim of the Project
The main goal of this project is to develop a predictive model that classifies students into different academic success categories (e.g., Graduate, Dropout, Enrolled). Key objectives include:

- 🧩 Identifying patterns that contribute to student success or failure.
- 📝 Providing insights to educators and policymakers for early intervention.
- 🎓 Enhancing academic planning and support mechanisms.

## 📊 Dataset Explanation
The dataset contains student records with both personal and academic attributes. The key features include:

- **Demographic Information:** Age at enrollment, gender, nationality, marital status.
- **Academic Background:** Previous qualification, admission grade, curricular unit performance.
- **Socioeconomic Factors:** Parents' education levels, occupations, unemployment rate, inflation rate, GDP.
- **Financial Status:** Scholarship status, tuition fee payment status.
- **Enrollment Information:** Application mode, attendance type (daytime/evening), special educational needs.
- **Target Variable:** The student's academic outcome, categorized as:
  - 🎓 Graduate: Successfully completed the program.
  - 💔 Dropout: Left the program before completion.
  - 📚 Enrolled: Still pursuing the program.

By analyzing these variables, we aim to build a model that predicts a student’s academic trajectory with high accuracy.

## 🔍 Model Performance Summary
Multiple machine learning models were implemented to predict student academic outcomes. The **Gradient Boosting Classifier** achieved the highest accuracy of **83.06%**, outperforming other models. Here’s a summary of the model performances:

| Model                           | Accuracy Score |
|----------------------------------|----------------|
| Gradient Boosting Classifier     | 0.8306         |
| Random Forest Classifier         | 0.8278         |
| Logistic Regression              | 0.8195         |
| Bernoulli Naive Bayes            | 0.7876         |
| KNeighbors Classifier            | 0.7785         |
| Gaussian Naive Bayes            | 0.7641         |
| Decision Tree Classifier         | 0.7405         |
| **Deep Learning Model**          | **0.8101**     |

### 🏆 Best Model: Gradient Boosting Classifier
The Gradient Boosting Classifier outperformed other models with the following classification results:
- **Dropout Prediction:** High precision (0.90) and good recall (0.83).
- **Graduate Prediction:** High recall (0.92) and strong F1-score (0.89).
- **Enrolled Prediction:** Slightly lower precision (0.65) and recall (0.61).

## 🔑 Key Insights & Future Improvements
- 📈 **Economic & Academic Factors Matter:** Admission grades, tuition payment status, and curricular performance significantly impact student outcomes.
- 🤖 **Machine Learning vs. Deep Learning:** Although the Gradient Boosting model outperformed deep learning, further optimization of the neural network might improve results.

## 💭 Final Thoughts
This study highlights the potential of predictive analytics in education. By leveraging machine learning, institutions can develop early warning systems to support at-risk students and improve overall academic success.

### Kaggle Notebook:
You can view and run the notebook for this project on Kaggle:  
[Classification with an Academic Success - Kaggle Notebook](https://www.kaggle.com/code/senasudemir/classification-with-an-academic-success) 🌐

## 🛠️ Technologies Used
- 🧑‍💻 **Python**
- 📊 **Scikit-learn**
- 🤖 **Gradient Boosting, Random Forest, Logistic Regression**
- 🧠 **Deep Learning (TensorFlow/Keras)**
