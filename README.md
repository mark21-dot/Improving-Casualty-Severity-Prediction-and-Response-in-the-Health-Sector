# Improving-Casualty-Severity-Prediction-and-Response-in-the-Health-Sector Using Machine Learning -  A case of UK Traffic
🚑 Project Objective
This project aims to develop machine learning models to accurately predict casualty severity in road accidents, thereby improving emergency response, resource allocation, and overall healthcare outcomes. By identifying high-risk cases early, healthcare systems can prioritize treatment and potentially save more lives.

📚 Table of Contents
Business Context

Data Loading and Preprocessing

Model Development

Model Evaluation

Results and Discussion

Future Work

🏥 Business Context
Accurate prediction of casualty severity is crucial for enhancing emergency medical services. Current systems often lack the ability to predict severity in real-time, resulting in suboptimal resource allocation and delayed interventions. This project builds predictive models using accident-related variables to address this gap.

Goals:

Predict casualty severity in road accidents

Support emergency response teams

Improve patient outcomes

Inform data-driven policy for road safety

🛠️ Data Loading and Preprocessing
Imported and cleaned the accident dataset (trainset_inspection.xlsx, testset_inspection.xlsx).

Conducted feature selection using Chi-Square Tests and Phi-K correlation to select the most relevant predictors.

Addressed class imbalance with SMOTE (Synthetic Minority Oversampling Technique).

🤖 Model Development
Built and evaluated the following machine learning models:

Decision Tree

Random Forest

AdaBoost

Support Vector Machine (SVM)

Logistic Regression

K-Nearest Neighbors (KNN)

Each model was hyperparameter tuned using GridSearchCV and evaluated on the training and test datasets.

📈 Model Evaluation
Models were compared based on Precision, Recall, and F1 Score.

Baseline Model: Dummy classifier for comparison

Best performing models: Random Forest and AdaBoost classifiers, achieving the highest macro F1 scores.

Minimal overfitting was observed due to robust cross-validation and tuning.

🔮 Future Work
Deploy the best model into a real-time dashboard for emergency services.

Integrate GPS, weather, and real-time traffic data for further prediction enhancement.

Explore Deep Learning methods (e.g., LSTM, GRU) for sequential data analysis.

🧑‍💻 Technologies Used
Python (Pandas, Numpy, Scikit-learn, Imbalanced-learn)

Matplotlib and Seaborn for visualization

Jupyter Notebooks

Joblib for model persistence
