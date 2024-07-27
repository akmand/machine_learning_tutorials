![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![License](https://img.shields.io/badge/License-MIT-brightgreen.svg)

# Machine Learning Tutorials with Scikit-Learn

Welcome to the Machine Learning Tutorials repository! This collection of Jupyter notebooks is designed to help you get started with machine learning using Python and Scikit-Learn. Whether you're a beginner or looking to deepen your understanding, these tutorials cover a range of topics from basic concepts to advanced techniques. These notebooks were written by yours truly, David Akman, and are my own work for the most part, except SK5 - Advanced Topics, for which my good friend [Chuck Wong](https://www.linkedin.com/in/yong-kai-wong/) contributed. They have been tested with Python 3.11.

## Table of Contents


### SK0_Scikit_Learn_Introduction.ipynb
This notebook introduces Scikit-Learn, covering its installation, data structures, and basic usage. It includes a simple example to illustrate how to create, train, and evaluate a machine learning model using Scikit-Learn.

### SK1_Basic_Modelling.ipynb
Focusing on basic machine learning models, this notebook guides users through the process of training and testing models. It explains key concepts like data splitting, model training, and performance evaluation using a linear regression example.

### SK2_Feature_Selection.ipynb
Feature selection techniques are critical for improving model performance. This notebook covers various methods such as univariate selection, recursive feature elimination, and tree-based selection, with practical examples demonstrating their implementation.

### SK3_Model_Evaluation.ipynb
This notebook dives into model evaluation metrics for classification and regression models, including accuracy, precision, recall, F1-score, and mean squared error. It also explains cross-validation and its importance in assessing model performance.

### SK4_HyperParameter_Tuning.ipynb
Hyperparameter tuning is essential for optimising machine learning models. This notebook explores grid search and random search techniques using Scikit-Learn’s `GridSearchCV` and `RandomizedSearchCV` classes, showing how to enhance model performance through proper tuning.

### SK5_Advanced_Topics.ipynb
Covering advanced machine learning topics, this notebook discusses model pipelines, statistical model comparison,  model deployment, and saving to and loading models from local storage. 

### SK6_Clustering.ipynb
This notebook explains clustering, an unsupervised learning technique, using algorithms including K-means and spectral clustering. Practical examples and visualisations illustrate how these algorithms work and their applications.

### SK7_Neural_Networks.ipynb
Introducing neural networks, this notebook covers the basics of building and training neural networks using Scikit-Learn and Tensorflow. It includes an example of a simple neural network for classification tasks.

### SK8_LightGBM.ipynb
LightGBM is a powerful gradient boosting framework. This notebook provides an introduction to LightGBM, demonstrating how to train and evaluate models using this library. Practical examples highlight its efficiency and performance benefits. This notebook also covers hyperparameter finetuning using Optuna (best in the business) and feature importance using the popular SHAP module.

### SK9_Forecasting.ipynb
Focusing on time series forecasting, this notebook covers essential techniques and models for making predictions based on temporal data using the Facebook Prophet Python module. 

### Case_Study1_Predicting_Income_Status.ipynb
This case study uses a real-world dataset to predict income status based on various features. It demonstrates the complete machine learning workflow, from data preprocessing and feature selection to model training, evaluation, and interpretation.

### Case_Study2_Maintenance_Predictive_Modelling.ipynb
This notebook presents a case study on predictive maintenance, showcasing how to predict equipment failures using historical data. It covers data preparation, model building, evaluation, and practical considerations for deployment.

### Data_Prep_for_Predictive_Modelling.ipynb
Data preparation is a critical step in the machine learning process. This notebook covers techniques for cleaning, transforming, and preparing data for predictive modeling, ensuring that the dataset is ready for analysis and model building.

### Decision_Trees_InfoGain_Computation.ipynb
Focusing on decision trees, this notebook explains how to compute information gain, an important concept for understanding tree-based models. It includes detailed examples and step-by-step calculations to illustrate the process.
