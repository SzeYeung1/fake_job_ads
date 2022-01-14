# Classification of Real and Fake Job Postings Using Ensemble Model
 
### Purpose
explore the characteristics of fake job postings and construct features to assist modelling
construct an ensemble model to distinguish real and fake job ads, using both textual analysis and non-textual features
 
### The Model
1. A bog-of-words (BoW) model using simple Countvectorizer and linear support vector machine (SVM)
1. A BoW model using TF-IDF vectorizer and random forest model
1. A XGBoost classifier model on the non-textual features
 
Each model is trained by different segment of the majority class (real ads) and full set of minority class (fake ads) from the training set upsampled, the predictions of the three models then take a simple majority vote for the final prediction
 
### Dataset
Employment Scam Aegean Dataset (EMSCAD) by researchers of University of the Aegean, consists of 17,800 job ads posted between 2012 to 2014 through Workable, a recruiting software, in which 866 job ads are marked as fraudulent. Downloadable at [EMSCAD](http://emscad.samos.aegean.gr/) and [Kaggle](https://www.kaggle.com/shivamb/real-or-fake-fake-jobposting-prediction)
 
### Bloglink
[Classification of Real and Fake Job Postings Using Ensemble Model](https://szeyeung.blogspot.com/2022/01/classification-of-real-and-fake.html)
