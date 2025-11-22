Task 5: Task 5: Decision Trees & Random Forest. 

This is a repository that constitutes my submission in Task 5 of the AI & ML Internship at Elevate Labs. This task was aimed to learn about tree-based models, overfitting analysis and apply ensemble learning methods.

Dataset
I have applied the Heart Disease Dataset (heart.csv) to forecast the occurrence of heart disease given different medical characteristics such as age, cholesterol, and the type of chest pain.

[?] Tech Stack
 Python
 Scikit-Learn (Sklearn)
 Pandas & NumPy
 Matplotlib & Seaborn (visualisation)

Key Implementation Steps

Data Processing: Prepared and divided the data on heart disease into training and test data.
Decision Tree: Trained one Decision Tree Classifier.
     Technique: entropy information gain used and maxdepth limited to avoid overfitting.
     Visualization: Bursting out the decision tree logic.
Random Forest: Applied a Random Forest Classifier that consisted of 100 trees.
     More accurate compared to the single tree model.
Importance of Features: Visualized and extracted what factors (e.g., Chest Pain, Thalassemia) were the most important to the prediction.
Validation: 5-Fold Cross-Validation was conducted to make sure that the model is stable.

Results & Observations
 Decision Tree Accuracy: 88 percent (depends on depth).
 Random Forest Accuracy: ~98% (Random Forest tended to be more effective than the single tree by minimizing variance).
 Top Features: The model has picked c p (Chest Pain), thal (Thalassemia), and ca (Number of major vessels) as significant predictors of heart disease.

How to Run
Clone the repo.
Dependency installation: pip install pandas numpy scikit-learn matplotlib seaborn.
Execute the script: python task5analysis.py.
