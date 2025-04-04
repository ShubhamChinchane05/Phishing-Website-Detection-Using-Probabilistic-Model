🛡️ Phishing Website Detection Using Probabilistic Model

This project focuses on identifying phishing websites using machine learning, specifically a probabilistic approach via Bernoulli Naive Bayes. The project includes data analysis, feature correlation, and comparisons between multiple classification models.

📊 Dataset

The dataset contains 30+ binary features that represent website attributes such as:

SSL certificate status

URL length and domain age

Presence of suspicious elements (e.g., @, redirects, popups)

Target: Result (1 = legitimate, -1 = phishing)

🔍 Workflow

Data Preprocessing (duplicates removal, reindexing)

Feature Correlation Analysis using heatmaps

Exploratory Data Analysis (count plots of features vs. target)

Model Building and Evaluation

🤖 Models Used

Support Vector Machine (🔑 Primary probabilistic model)

Logistic Regression

Random Forest

K-Nearest Neighbors

Bernoulli Naive Bayes

Decision Tree

AdaBoost

📈 Evaluation Metrics

The following metrics were used for model evaluation:

Accuracy

Precision, Recall, F1-score

ROC AUC Score

🏆 Best Model (Suggested): Support Vector Machine

This model was the focal point of the project and represents the probabilistic approach for phishing website detection.
