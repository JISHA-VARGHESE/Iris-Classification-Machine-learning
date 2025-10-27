Iris Flower Classification

Problem Statement

The Iris flower includes three main species: Iris Setosa, Iris Versicolor, and Iris Virginica.
They differ in sepal length, sepal width, petal length, and petal width.
The goal is to build a machine learning model that classifies Iris flowers automatically based on these measurements.

Objective

To develop a classification model that accurately identifies the species of Iris flowers using their physical features and automates the identification process.

Project Details

Dataset: Iris dataset (Setosa, Versicolor, Virginica)

Features Used: Sepal Length, Sepal Width, Petal Length, Petal Width

Models Tested: Decision Tree, Random Forest, Naive Bayes

Final Model: Tuned Random Forest Classifier

Model Evaluation (Recall as Key Metric)
Sl. No	Classification Model	Recall Train (%)	Recall Test (%)
1	Decision Tree (Tuned)	95.24	95.56
2	Random Forest (Tuned)	97.14	97.78
3	Naive Bayes	94.28	97.78
4	Naive Bayes (Tuned)	94.28	97.78
Conclusion

The tuned Random Forest model was selected as the final prediction model.

The model achieved high recall and accuracy in classifying Iris species.

Iris-Setosa showed distinct characteristics compared to the other two species.

Data preprocessing involved cleaning, handling missing values, and encoding variables.

Future Scope: Explore advanced models to further enhance accuracy.

Applications: Useful in botany and horticulture for automating species identification.

Technologies Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn
