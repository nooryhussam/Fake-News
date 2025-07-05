📰 Fake News Detection Project

📌 Project Idea
In this project, I worked on building a system that can detect fake news by classifying news articles as real or fake. My main goal was to see how feature extraction and dimensionality reduction affect the model’s accuracy.

🎯 Objective
Build a baseline classification model using raw text data.

Apply feature extraction techniques like TF-IDF to convert text into numbers.

Use PCA to reduce the number of features and compare the performance before and after.

Analyze if these processing steps improve or worsen accuracy.

🛠️ Technologies I Used
Python

Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, nltk

🗂️ Dataset
I used the Fake and Real News dataset from Kaggle, which has labeled articles as real or fake.

🔄 My Workflow
Cleaned and preprocessed the text data.

Built a baseline Logistic Regression model using the raw text.

Converted the text into numeric features with TF-IDF.

Reduced the feature dimensions using PCA.

Retrained the model on the reduced features.

Compared results between the baseline and the improved model.

📊 Results
Baseline accuracy: (put your result here)

Accuracy after TF-IDF + PCA: (put your result here)

Observation: Did performance improve or drop? Was the processing faster or slower?

