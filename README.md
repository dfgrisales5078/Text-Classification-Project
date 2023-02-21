# Project 1 - Text Classification Using Multinomial (Naive Bayes Model) & Multi-Layer Perceptron (Neural Network Model)

## Conclusion
In conclusion, based on the data presented above we can conclude that the Neural Network model classifier using the MLPClassifier and Tf-Idf is the most accurate and precise of all the models. The coronavirus data using the Neural Network model in combination with Tf-Idf resulted in the highest score across the board. The data shows an astonishing 83.3% precision with 82.7% accuracy score, and 82.0 recall score. We start by separating each corpus into text and labels to create a numeric bag of word matrix, because the MLPClassifier only uses numeric matrices. After creating the bag of words, we start to train the model to predict the test labels. As a result, the data displayed most accurately based on the prediction of MLPClassifier model. Therefore, the confusion matrix shows a large amount of vocabulary being true negative, and true positive which displayed that the negative vocabulary is negative, and the positive vocabulary are actually positive.


## The Coronavirus Data Set:
The data contained in the csv was read with custom delimiter | pipe. The unique labels are 1 for (positive) and 0 for (negative) which represent a sentiment value. This is based on the comments and posts related to the COVID-19 pandemic. Using sentiment classification can help understand the mood of the posts or comments. Total records in the dev data file were 10,000 and in the train data file there were 80,000. The dev data contained 4,963 negative and 5,037 positive posts or comments. However, the train data contained 38,837 negative and 41,163 positive posts or comments. In the train data set, there were 81,647 unique terms and the dev data set had the same number of unique terms 81,647.


## The Triage Data Set:
The data contained in the csv was read with custom delimiter | pipe. The unique labels are 1 for (aid-related) and 0 for (non-aid-related). These labels are the classification of each document by requests for food, water, shelter, and reports about life-or-death situations and disaster relief. An obstacle related to the data is that it was crowdsourced which may contain words from other languages or inaccurate translations. Total records in the dev data file were 2,573 and in the train data file were 21,046. In the dev data set, there are 1,525 non-aid-related and 1,048 aid-related documents, but in the train data set there are 12,361 non-aid-related and 8,685 aid-related documents. In the train data set, there were 31,211 unique terms and the dev data set had the same amount 31,211.


