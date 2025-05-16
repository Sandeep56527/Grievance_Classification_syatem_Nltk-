Grievance-Classification-System
This project applies Natural Language Processing and Machine Learning to classify customer complaints into categories like credit reporting, loans, and credit cards. It uses techniques such as stopword removal, bag-of-words. Ideal for anyone exploring practical NLP applications in the financial domain.

📌 Problem Statement
The aim was to automate the categorization of customer grievances submitted to financial institutions, enabling better issue tracking, response prioritization, and service improvement.

📂 Dataset
The dataset included consumer complaints with fields such as:

Consumer Complaint Narrative
Issue
Sub-issue
Product
Company
State
For context-rich analysis, I combined the Narrative, Issue, and Sub-issue into a single text feature.

🔍 Preprocessing & NLP
The complaint text was cleaned and prepared using standard NLP techniques:

Removal of punctuation
Text normalization (lowercasing)
Stopword removal (using NLTK)
Feature extraction using CountVectorizer (Bag-of-Words)
🤖 Models & Evaluation
I trained and evaluated the following classifiers:

Logistic Regression
Naive Bayes
Decision Tree (🏆 Best Performer – 94% Accuracy)
Evaluation Metrics:
Accuracy
Precision
Recall
F1-Score
🚀 Key Learnings
Practical implementation of text classification
Feature engineering with NLP
Real-world complaint data handling
Insight generation for customer service and compliance improvement
🧰 Tech Stack
Python
Pandas, NumPy
NLTK
Scikit-learn
