# Text-Mining
Sentimental Analysis

For Code refer to code_nagarathna_sali.py
For Detailed analysis report about the task refer to Report_Nagarathna_Sali
To refer to dataset used for this project refer to user_reviews.csv
To refer to dataset used for this project refer to test_reviews.csv

In this task I created Three classification models (using three different classification 
algorithms) in Python that can predict whether users will recommend products to others or 
not. The Models created are :
1. Support vector Classifier
2. Naive Bayse Classifier
3. Adaptive Boosting(Ada Boost)

The above 3 mentioned  models were created under each of the following scenarios:
1. Only unigrams are used as tokens, which must occur in at least 10 documents.
2. Unigrams and Bigrams are used as tokens, which must occur in at least 20 documents.
3. Unigrams, Bigrams and Trigrams are used as tokens, which must occur in at least 30 
documents. 

The Dataset used for this project is user_reviews

About the dataset : The dataset user_reviews.csv contains 100,000 user reviews of smartphones or their 
accessories. This data has been scraped from multiple websites, and all variables in the dataset 
are self-explanatory. In addition to the user reviews, user scores (out of 10) are also available.
It is assumed that a user will recommend a given product to others if the score given by that 
user is >= 8. Otherwise, it is assumed that the user will not recommend the product to others.

Dataset used for deployment of the built model to predict users’ recommendations is the test_reviews.csv dataset.
