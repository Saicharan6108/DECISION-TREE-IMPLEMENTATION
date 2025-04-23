# DECISION-TREE-IMPLEMENTATION

*COMPANY*: CODTECH IT SOLUTIONS  

*NAME*: MOLIGE SAI CHARAN  

*INTERN ID*: CT04WY43  

*DOMAIN*: MACHINE LEARNING  

*DURATION*: 4 WEEKS  

*MENTOR*: NEELA SANTOSH



Project Overview:

This project focuses on implementing and visualizing a Decision Tree classifier using the popular scikit-learn library. It is part of the first task assigned during my machine learning internship at Codtech IT Solutions. The objective is to explore the fundamentals of supervised learning by creating a classification model capable of predicting outcomes from a well-known dataset.

For this implementation, I utilized the Iris dataset, a classical machine learning dataset that contains measurements of iris flowers from three different species. The main goal was to classify these flowers based on four features: sepal length, sepal width, petal length, and petal width.

Tools & Libraries Used:

Python: Core programming language used for scripting the entire project.

Pandas: For loading and organizing the dataset into dataframes for easy manipulation and analysis.

Scikit-learn (sklearn):

DecisionTreeClassifier: Used to build the decision tree model.

train_test_split: To split the dataset into training and testing subsets.

accuracy_score and classification_report: To evaluate the model's performance.

plot_tree: For visualization of the trained decision tree.

Matplotlib: Used for plotting the decision tree for a clear and interpretable visualization.

Steps Followed:

1. Data Loading
The Iris dataset was loaded using sklearn.datasets.load_iris(). This dataset consists of 150 samples equally divided into three classes.

2. Data Splitting
The data was split into 80% training and 20% testing using train_test_split() with a fixed random seed (random_state=42) to ensure reproducibility.

3. Model Building
A DecisionTreeClassifier was instantiated and trained on the training dataset. The model learned decision rules from the features to predict the target variable (iris species).

4. Model Prediction
The trained model was used to make predictions on the unseen testing set.

5. Model Evaluation
Model performance was assessed using:

Accuracy Score: Indicates the percentage of correct predictions.

Classification Report: Shows precision, recall, f1-score, and support for each class.

6. Visualization
The decision tree was visualized using plot_tree(), providing insights into how decisions are made at each node. The plot includes feature names, class names, node purity, and sample sizes.

Output Highlights
The model achieved high accuracy, confirming that a decision tree is a good classifier for the Iris dataset.

The visualization clearly outlines the splits made by the model based on feature thresholds, making it interpretable for users and stakeholders.

Deliverable:

A Jupyter Notebook containing:

Data preparation steps

Model training and evaluation

Visualizations of the decision tree

In-depth analysis and observations

Conclusion:

This task laid a solid foundation in understanding how decision trees work in a machine learning pipeline. It also demonstrated the importance of data visualization in interpreting model decisions. Moving forward, I aim to explore more complex models and datasets, building upon this foundational task.

