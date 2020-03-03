# Logistic-Regression-using-Encoder-Decoder-Dimensionality-Reduction
1. I try to compare the performance of simple Logistic Regression on the text classification using tf-idf vectorizer vs when I try to reduce the dimension of the tf-idf vectorizer using encoder-decoder. 
2. Both the models are giving almost equal results.
3. In case of encoder-decoder, I have not done hyperparameter tunning, it may increase the performance of the encoder-decoder based dimensionality reduction model.
4. It was really fun to see the results, when we are using encoder as dimensionality reduction tools.

## Steps for encoder-decoder based model:
1. Data Cleaning
2. Vectorize the dataset using tfidf
3. Reduce the dimensions of the dataset using encoder
4. Apply Logistic Regression

## Steps for Simple Logistic Regression based model:
1. Data Cleaning
2. Vectorize the dataset using tfidf
3. Apply Logistic Regression
