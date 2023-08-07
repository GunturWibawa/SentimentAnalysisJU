# SentimentAnalysisJU

Sentiment Analysis of Junky Union Movie Community

The project assigned to me during the fourteenth sprint involves Machine Learning for Text.

Throughout this sprint, I dived into machine learning for text on its key principles including lemmatization, TF-IDF, sentiment analysis, and embedding BERT model to transform words into vector.

# **Project Insight**

Junky Union, a new community dedicated to fans of classic cinema, is in the process of constructing a sophisticated system to filter and categorize movie critiques. The principal objective of this endeavor is to design an analytical model that capable to detect negative reviews intelligently. For this purpose, I will utilize the IMBD movie review dataset, complete with polarity labeling, to engineer a model that can systematically classify the reviews as either positive or negative. The aspiration is to reach a model precision characterized by an F1 score of no less than 0.85.

Following the completion of a further experiment involving four distinct models, the summarized F1 scores are as follows:

1. Model 1 - Comprising NLTK, TF-IDF, and Logistic Regression, this model yielded an F1 score of 0.82 (train) and 0.83 (test).
2. Model 3 - Integrating spaCy, TF-IDF, and Logistic Regression, this model achieved an F1 score of 0.83 (train) and 0.83 (test).
3. Model 4 - A blend of spaCy, TF-IDF, and LightGBM, this model recorded an F1 score of 0.77 (train) and 0.76 (test).
4. Model 9 - The BERT model, standing out from the rest, produced an impressive F1 score of 0.90 (train) and 0.84 (test).

It is necessary that BERT was the sole model to surpass the F1 score threshold of 0.85. This achievement, however, was confined to a limited sample of 14,000, owing to the constraints of CPU-based computation. I firmly believe that by harnessing the entire dataset for training, not only will the desired threshold be met, but this particular model may also outperform the others, shows more promising results.
