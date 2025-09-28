# email-spam-detector
This project is a simple machine learning model that can check if an email/message is Spam (unwanted) or Ham (normal).

**How it works**

1.We take a dataset of emails (spam + ham).

2.We clean the text (remove unwanted characters, split into words).

3.We convert words into numbers using CountVectorizer or TF-IDF.

4.We train a Naive Bayes algorithm (MultinomialNB / BernoulliNB).

5.The model learns patterns of spam words like “free, win, prize”.

6.When we give a new message, the model predicts Spam or Ham.

**Tools & Libraries Used**

1.Python 

2.Pandas → for handling data

3.Matplotlib / Seaborn → for graphs

4.NLTK → for text processing

5.Scikit-learn → for ML algorithms (Naive Bayes, train/test split, accuracy, precision, etc.)

This project is a beginner-friendly ML project that shows how machine learning can be used in real life to filter unwanted spam emails.
