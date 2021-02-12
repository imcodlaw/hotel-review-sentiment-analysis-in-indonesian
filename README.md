# hotel-review-sentiment-analysis-in-indonesian

Sentiment analysis is one of the most common example of text classification. Basically the goal of sentiment analysis is to classify data which consist of sentences into classes like negative, positive, or neutral sentiment. In this analysis, there are only 2 classes (negative and positive). 


The obtained dataset is a collection of hotel reviews by customers in Bahasa Indonesia (Indonesian). In this project we used the Indonesian version of Bidirectional Encoder Representations from Transformers (BERT) based on this paper https://www.aclweb.org/anthology/2020.aacl-main.85.pdf and this github repo https://github.com/indobenchmark/indonlu.


We used the large finetuning indoBERT and managed to surpass other text classfier methods with approx 92% score on macro F1-score.
