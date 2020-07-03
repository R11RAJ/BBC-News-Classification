# BBC-News-Classification
Classifying BBC news articles using a single classifier and an Ensemble Classifer.

# Datasets used
Kaggle BBC news article datasets, it consist of 5 categories : Business,Entertainment,Politics,Sport and Technology.

# Dependencies
NLTK Corpus
Google Pre-computed Word2Vec embeddings
Gensim library

# Text Representation
TFIDF,Word2Vec

# Classification
<ul>
<li>Single Classifier : SVM </li>
<li>Ensemble
    <ul>
      <li>Voting classifier : Logistic regression, Random Forest classifier, Multinomial gaussian</li>
      <li>Stacking classifier:  Random Forest classifier, Multinomial gaussian
                         <br>Meta Classifier : Logistic regression</li>
  </ul></li>
</ul>

# Performance Metrics
Precision recall and F1 Score for single classifier SVM.
96% precision and recall for single classifier.

Accuracy for Ensemble classifier, 98% accuracy achieved.
