# Email-Spam-Classifier

This project is an Email Spam Classifier built using Python and Machine Learning.
The model is trained to classify emails into two categories:

Spam (0) → Unwanted or junk emails.

Ham (1) → Legitimate emails.

The classifier uses the TF-IDF Vectorizer for text feature extraction and Logistic Regression for classification.

## Features
Load and preprocess email data from CSV file.

Convert text data into numerical features using TF-IDF.

Train a Logistic Regression model to classify emails.

Evaluate model performance with training and testing accuracy.

Visualize:

Spam vs Ham distribution.

Accuracy comparison between training and testing datasets.

Test custom email inputs to check predictions.

## Dataset
The dataset used is mail_data.csv which contains:

Category → Spam or Ham

Message → Email text content

## Libraries Used
Pandas → Data loading and processing

NumPy → Numerical computations

Matplotlib & Seaborn → Visualization

Scikit-learn → Machine learning model & evaluation
