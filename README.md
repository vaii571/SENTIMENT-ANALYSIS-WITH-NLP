# SENTIMENT-ANALYSIS-WITH-NLP



_COMPANY_: CODTECH IT SOLUTIONS


_NAME_: VAISHNAVI VILAS BANSUDE


_INTERN ID_: CTIS4923


_DOMAIN_: MACHINE LEARNING


_DURATION_: 4 WEEKS


_MENTOR_: NEELA SANTOSH KUMAR

DESCRIPTION OF TASK:

Title: Sentiment Analysis on Customer Reviews Using TF-IDF and Logistic Regression

Introduction:

Sentiment Analysis is a Natural Language Processing (NLP) technique used to determine the emotional tone behind textual data. It helps in identifying whether a piece of text expresses a positive, negative, or neutral opinion. In today’s digital world, customers frequently share their opinions on social media platforms and review websites. Analyzing this feedback manually is difficult due to the large volume of data. Therefore, machine learning techniques can be used to automate the sentiment classification process.

This project focuses on performing sentiment analysis on a dataset of customer reviews (Twitter data) using TF-IDF vectorization and Logistic Regression. The main objective is to classify tweets into positive or negative sentiments and evaluate the model’s performance.

Data Collection and Exploration:

The dataset used in this project consists of tweets along with their sentiment labels. The label column contains binary values where:
0 represents Negative sentiment
1 represents Positive sentiment
Initially, the dataset was loaded using the Pandas library, and the distribution of positive and negative classes was examined to understand class balance.

Text Preprocessing:

Raw text data often contains noise such as URLs, user mentions, special characters, and extra spaces. To improve model performance, preprocessing was performed. The preprocessing steps included:
Converting text to lowercase
Removing URLs
Removing user mentions (@username)
Removing special characters and numbers
Removing extra spaces
The cleaned text was stored in a new column called clean_tweet. Proper preprocessing ensures that the model learns meaningful patterns rather than irrelevant symbols.

Data Balancing:

To prevent bias in predictions, the dataset was balanced by selecting an equal number of positive and negative samples. Balanced data helps the model learn both classes equally and improves fairness in classification.

Feature Extraction using TF-IDF:

Since machine learning models cannot directly process text data, the cleaned tweets were converted into numerical format using TF-IDF (Term Frequency–Inverse Document Frequency).
TF-IDF assigns weights to words based on their importance in the document and across the dataset. Unigrams and bigrams were used to capture better contextual meaning. This step transformed text data into feature vectors suitable for training the model.

Model Training Using Logistic Regression:

The dataset was split into training and testing sets using an 80-20 ratio. Logistic Regression was selected as the classification algorithm because it is efficient and performs well for binary classification problems.
The model was trained using the training data and then used to predict sentiments on the test data.

Model Evaluation:

To evaluate performance, the following metrics were used:

Accuracy Score – Measures overall correctness

Confusion Matrix – Displays correct and incorrect predictions

Classification Report – Shows precision, recall, and F1-score

Additionally, bar charts were plotted to visualize the distribution of positive and negative sentiments.

Conclusion:

This project successfully demonstrates how sentiment analysis can be performed using NLP techniques. By applying text preprocessing, TF-IDF vectorization, and Logistic Regression, the model effectively classifies customer reviews as positive or negative. The Jupyter Notebook includes preprocessing, modeling, evaluation, and visualization, fulfilling all requirements.

OUTPUT

<img width="539" height="455" alt="Image" src="https://github.com/user-attachments/assets/9af713a9-bac7-495f-9900-2104623d7466" />

<img width="901" height="337" alt="Image" src="https://github.com/user-attachments/assets/36a701b1-e523-4780-bc86-1bc82d98cdad" />

<img width="716" height="477" alt="Image" src="https://github.com/user-attachments/assets/4515fbb4-38f5-4bfc-8a21-1d5f04a47203" />

<img width="571" height="455" alt="Image" src="https://github.com/user-attachments/assets/9fcb46ad-7635-476e-8af0-667f20234543" />


