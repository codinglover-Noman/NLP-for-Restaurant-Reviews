# NLP-for-Restaurant-Reviews
This project based on Restaurant customer reviews using natural language processing. The sample dataset consists of 1000 reviews from an un-named restaurant. The aim is to predict the sentiment of the review(Positive or negative).

## Road map of this project: 

At first, we need to do text cleaning. It involves:
 
 1.Removing punctuations(In our case we will not remove apostrophe as it is used in negation words like didn't isn't etc, that shows sentiment)
 2.Removing stopwords like articles, prounouns etc.(Here we will exclude the stopwords that will indicate sentiments like no, not etc.
 3.Changing our case to lower case
 4.Stemming the words in order to get the root of the word.(This is done to optimise the sparse matrix that will be formed by the CountVectoriser)
 5.Making the Bag Of Words Model by using the CountVectoriser class imported from sklearn.
 6.Building any classification model. 

 ## Model used for this project:
 * Logistric Regression
 * Naive Bays
 * Support Vector Machine

## Conclusion: 
Logistic regression gave the best performance with 82% accuracy.
