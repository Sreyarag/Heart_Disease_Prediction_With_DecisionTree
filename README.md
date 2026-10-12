❤️ Heart Disease Prediction Using Decision Tree

📌 Project Overview

This project uses Machine Learning to predict the presence or absence of heart disease based on clinical features such as age, chest pain type, blood pressure, cholesterol, and maximum heart rate.

A Decision Tree Classifier is trained and evaluated using Python and Scikit-learn.

🎯 Objectives

- Build a Decision Tree classification model.
- Explore and preprocess the heart disease dataset.
- Evaluate model performance using classification metrics.
- Visualize the decision tree and feature importance.
- Tune the model's maximum depth using cross-validation.

🛠️ Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

📂 Dataset

The dataset contains 270 records, 13 input features, and one target column named "heart disease".

- "1" — Absence of heart disease
- "2" — Presence of heart disease

⚙️ Methodology

1. Load and explore the dataset.
2. Check for missing values.
3. Separate input features and the target variable.
4. Split the data into 80% training and 20% testing sets.
5. Train a Decision Tree Classifier using Gini impurity.
6. Evaluate the model using accuracy, precision, recall, F1-score, and a confusion matrix.
7. Compare different tree depths using 5-fold cross-validation.
8. Visualize the decision tree and feature importance.

📊 Results

- Test Accuracy: 79.63%
- Best tested tree depth: 4
- Mean 5-fold cross-validation accuracy: 74.55%
- Evaluation metrics: Precision, recall, F1-score, and confusion matrix.
- Most important feature in the trained model: Chest pain type.

🚀 How to Run

1. Clone or download this repository.
2. Open the notebook in Google Colab.
3. Upload the dataset CSV file.
4. Run the code cells in order.
5. Review the model predictions, evaluation metrics, and visualizations.

🔮 Future Improvements

- Compare Decision Tree with Random Forest and other classifiers.
- Use hyperparameter tuning to improve generalization.
- Evaluate performance on additional datasets.
- Develop a simple interface for educational demonstrations.

⚠️ Disclaimer

This project is for educational purposes only. The model is not clinically validated and must not be used for medical diagnosis or treatment decisions.

👩‍💻 Author

Sreya

Machine Learning Project | Python | Scikit-learn
