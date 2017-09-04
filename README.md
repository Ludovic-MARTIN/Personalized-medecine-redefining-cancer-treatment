# Personalized-medecine-redefining-cancer-treatment
Predict the effect of Genetic Variants to enable Personalized Medicine

Files required :


Libraries:
__________
To do it the main libraries required are numpy, pandas, matplotlib, seaborn.

We also use the library gensim.models.word2vec that permits to evaluate word proximity in the corpus.

The TfidfVectorizer will vectorize the texts and permit to work with it.

The high cardinality of Variants will produce high number of features as vectorization does.
We use TruncatedSVD to reduce feature number.

Finally, we build our model with xgboost and evaluate 5 folders from sklearn.model_selection.train_test_split
with sklearn.metrics 

