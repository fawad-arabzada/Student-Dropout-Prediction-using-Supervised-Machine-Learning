# Student-Dropout-Prediction-using-Supervised-Machine-Learning
Student Dropout Prediction using Supervised Machine Learning is a data-driven project that aims to address a major challenge in higher education: student dropout. Dropping out can have serious social, financial, and institutional consequences. By predicting dropout risks early, educational institutions can provide timely support and improve overall student retention.

In this project, we use real-world student data and apply a full machine learning pipeline to accurately predict whether a student is at risk of dropping out. The entire process includes:
🔍 1. Data Preprocessing

    Handling Missing Values: We cleaned the dataset by removing or imputing missing and inconsistent values to ensure data quality.

    Feature Engineering: We created new features and refined existing ones to improve model accuracy.

    Encoding Categorical Variables: Applied One-Hot Encoding for nominal features to prepare the data for machine learning models.

    Feature Scaling: Used Standardization (Z-score) to normalize numerical features for optimal model performance.

    Data Splitting: The dataset was divided into training and testing sets (80% training, 20% testing) using train_test_split with stratified sampling to maintain class balance.

🎯 2. Target Definition

We converted the original target variable into a binary classification:

    1 → Dropout

    0 → Not Dropout (i.e., students who graduated or are still enrolled)

This simplified the problem and made it suitable for binary classification models.
🧠 3. Machine Learning Models

We trained and compared the performance of four supervised learning models:

    Logistic Regression

    Decision Tree Classifier

    Random Forest Classifier

    Support Vector Machine (SVM)

Each model was evaluated using the following performance metrics:

    Accuracy

    Precision

    Recall

    F1-Score

    ROC-AUC Score

📈 4. Results & Insights

    The Random Forest Classifier delivered the highest performance, with an accuracy of ~89%.

    We also performed Feature Importance Analysis to identify the most influential factors contributing to dropout.

    Visualizations were created to highlight class imbalance, feature distribution, and model comparisons.

📊 5. Visualizations

We included several graphs and charts to make the analysis visually intuitive:

    Bar plots for feature importance

    Pie chart or bar graph for dropout class distribution

    ROC curves for model comparison

    Optional confusion matrices to visualize prediction performance

🛠️ Tools & Technologies Used

    Python

    Pandas, NumPy – for data manipulation

    Matplotlib, Seaborn – for data visualization

    Scikit-learn – for machine learning models and evaluation

🌟 Why This Project Matters

Educational institutions often struggle to identify students at risk of dropping out until it's too late. With this model:

    Administrators can proactively support students showing early signs of disengagement.

    Policies can be crafted based on data-backed insights.

    It contributes to building a more inclusive and supportive academic environment.
