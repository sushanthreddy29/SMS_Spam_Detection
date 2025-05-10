SMS Spam Detection

Introduction
This documentation outlines the SMS Spam Detection project, which centers on classifying text messages to distinguish spam from legitimate content. The project uses Python along with libraries such as NumPy, pandas, Matplotlib, Seaborn, TensorFlow, and Scikit-learn to implement and evaluate various machine learning models.


Project Objective
The goal is to build and compare multiple machine learning models tailored for text classification, with a focus on identifying spam messages. By assessing different algorithms, users can better understand their performance and select the best-suited model for their specific needs.


Key Features

Data Handling & Preprocessing: Load the dataset, clean the text, and prepare it for analysis.

Data Analysis & Visualization: Use charts and plots to explore and illustrate patterns in the data.

Model Development: Implement a range of models including Naive Bayes, custom neural networks, Bidirectional LSTM, and models using Transfer Learning.

Model Evaluation: Measure performance using metrics such as accuracy, precision, recall, and F1-score.

Model Comparison: Analyze and compare results across models to determine the most effective approach.


How to Use the Project

Ensure Python and all required libraries are installed.

Download the source code and dataset (spam.csv).

Execute the code in sequence within a Python environment.

Review the outcomes and compare how each model performs.

Detailed Workflow

Loading and Preprocessing the Data:

Import the dataset using pandas.

Clean the data by dropping unnecessary columns, renaming headers, and converting labels into numerical form.

Exploring and Visualizing the Data:

Use plots to analyze the distribution of spam vs. non-spam messages.

Study message lengths and how they vary across message types.

Building the Models:

Naive Bayes

Neural Network with custom word embeddings

Bidirectional LSTM

Transfer Learning using the Universal Sentence Encoder

Evaluating the Models:

Assess each model’s performance using key classification metrics.

Generate confusion matrices and classification reports.

Comparing Models:

Evaluate model performance side-by-side based on accuracy, precision, recall, and F1-score.

Use visual aids like bar graphs to illustrate the results.


Model Insights

Naive Bayes:

Achieves an accuracy of X%, with precision, recall, and F1-score of X%.

Uses word frequency to estimate the likelihood of spam.

Assumes feature independence, which may not always be accurate but works well for simple text classification.

Neural Networks with Custom Embeddings:

Attains X% accuracy and corresponding precision, recall, and F1-score.

Architecture includes embeddings, LSTM, dropout, and dense layers with ReLU activation.

Captures word relationships and sequences more effectively than traditional models.

Bidirectional LSTM:

Achieves X% accuracy, along with respective precision, recall, and F1-score.

Processes input in both forward and backward directions, enhancing context awareness.

Particularly strong at learning long-term dependencies in sequential data.

Transfer Learning with Universal Sentence Encoder:

Records an accuracy of X% and relevant metric scores.

Uses pre-trained embeddings that encapsulate the semantic meaning of entire sentences.

Especially useful when working with smaller or specialized datasets.

Performance Comparison

Accuracy: Analyze which model is most accurate.

Precision vs. Recall: Evaluate the balance between identifying spam and avoiding false positives.

F1-score: Compare F1-scores to gauge overall effectiveness.


Conclusion
This project offers a complete pipeline for tackling SMS spam detection—from data preparation to model comparison. It serves as a hands-on guide for anyone interested in exploring text classification techniques and deploying spam filters using machine learning.
