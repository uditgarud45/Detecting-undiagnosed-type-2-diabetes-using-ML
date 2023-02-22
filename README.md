# Detecting-undiagnosed-type-2-diabetes-using-ML

Health Prediction using Machine Learning
This project is a machine learning-based health prediction system that predicts whether a patient has a risk of cardiovascular disease. The model was developed using Python and scikit-learn, and it was trained on a dataset with 70,000 patient records.

Data Cleaning and Preprocessing
The data was cleaned and preprocessed before being used to train the model. The missing values were replaced with mean values, and new features were engineered, such as waist-to-height ratio and waist-to-stature ratio. The data was also categorized into distinct bins, and unnecessary columns were dropped.

Modeling
Three classifiers were used to train the model, including logistic regression, random forest, and support vector machine. A voting classifier was used to combine the predictions of the individual classifiers. The accuracy, recall, confusion matrix, and classification report for each classifier were calculated.

Feature Selection
Feature selection was performed using the chi-squared statistical test for non-negative features. The random forest classifier was used to fit the classifier on the training data, and predictions were produced on the test data. The algorithm then calculated the accuracy, recall, confusion matrix, and classification report for the classifier.

Results
The random forest classifier was found to be the best classifier among the three tested, with an accuracy of 0.94 and a recall of 0.90 when using the top 5 features (Glucose, Age, Cholesterol, waist, and weight2) for analysis.

Usage
To use the model, simply run the Jupyter notebook provided in the repository. The notebook includes all the code and instructions needed to load the dataset, train the model, and make predictions.

Conclusion
In conclusion, this project demonstrates the use of machine learning in predicting health outcomes. The model achieved high accuracy and recall, which could help doctors and healthcare providers identify patients at risk of cardiovascular disease early and take preventive measures.
