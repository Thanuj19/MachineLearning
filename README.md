This repository contains several ML models which I created in School

THE FIRST IS FAKE NEWS DETECTION:
This code implements a machine learning model to classify news articles as either real or fake. It utilizes a Passive Aggressive Classifier, a type of online learning algorithm, along with a Term Frequency-Inverse Document Frequency (TF-IDF) vectorizer for feature extraction. Here's a breakdown of the steps:

1. **Data Preparation:** The code first reads in a dataset (`news.csv`) containing news articles along with their corresponding labels (real or fake).

2. **Data Preprocessing:** It preprocesses the data by splitting it into training and testing sets, and extracts the labels.

3. **Feature Extraction:** It uses a TF-IDF vectorizer to convert the textual data into numerical features, which represent the importance of each word in the context of the entire dataset.

4. **Model Training:** The Passive Aggressive Classifier is initialized and trained on the TF-IDF transformed training data. This classifier is well-suited for online learning scenarios and is particularly effective in handling large streams of data.

5. **Model Evaluation:** After training, the model makes predictions on the testing data. The accuracy of the model is calculated and printed, indicating how well it performs at distinguishing between real and fake news articles.

6. **Performance Evaluation:** Finally, a confusion matrix is generated to provide a detailed breakdown of the model's predictions, enabling an assessment of its performance in terms of true positives, false positives, true negatives, and false negatives.

Overall, this code showcases a practical application of machine learning techniques for detecting fake news, a task of considerable importance in today's information landscape.

