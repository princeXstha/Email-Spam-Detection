# Email-Spam-Detection
🔍 Overview

This project implements a text classification model to detect spam messages using natural language processing (NLP) and machine learning techniques. By leveraging the SMS Spam Collection Dataset, it builds a robust pipeline from data cleaning to model evaluation, showcasing the practical use of classical ML in real-world email filtering.

🗂️ Dataset

Source: UCI SMS Spam Collection Dataset
Content: 5,572 SMS messages labeled as either:
ham — legitimate message
spam — unsolicited promotional or malicious message

🧰 Technologies Used

Programming Language: Python
Libraries:
pandas, numpy – data handling
matplotlib, seaborn – visualization
nltk – text preprocessing (tokenization, stemming)
scikit-learn – model training, TF-IDF, evaluation

🔧 Workflow
Data Cleaning
Dropped null and redundant columns
Removed duplicates
Label encoding for categorical variables
Exploratory Data Analysis (EDA)
Statistical comparison between spam and ham messages
Visual plots for message length, word count
Text Preprocessing
Tokenization, stemming, stopword removal
TF-IDF vectorization for feature extraction
Modeling
Algorithm: Multinomial Naive Bayes
Split: Train-test using train_test_split
Evaluation: Accuracy, Precision, Recall, Confusion Matrix

📊 Results
Achieved high accuracy in classifying messages
Balanced performance across precision and recall
Validated effectiveness of classical NLP pipeline

📁 Project Structure
emailspam.ipynb       # Main Jupyter Notebook
spam.csv              # Dataset
README.md             # Project documentation

✅ How to Run
Clone the repository
Install dependencies:
pip install pandas numpy matplotlib seaborn scikit-learn nltk
Run the emailspam.ipynb notebook step-by-step
