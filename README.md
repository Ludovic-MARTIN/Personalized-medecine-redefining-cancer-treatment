# Personalized-medecine-redefining-cancer-treatment
Predict the effect of Genetic Variants to enable Personalized Medicine

Files required :
________________
The two next files are located in the repository that the notebook :
test_variants
training_variants

The two following files are too heavy to be recorded on github, you can dowload them form this URL : 
https://www.kaggle.com/c/msk-redefining-cancer-treatment/data

training_text
test_text


Libraries:
__________
To do it the main libraries required are numpy, pandas, matplotlib, seaborn.

We also use the library gensim.models.word2vec that permits to evaluate word proximity in the corpus.

The TfidfVectorizer will vectorize the texts and permit to work with it.

The high cardinality of Variants will produce high number of features as vectorization does.
We use TruncatedSVD to reduce feature number.

Finally, we build our model with xgboost and evaluate 5 folders from sklearn.model_selection.train_test_split
with sklearn.metrics 

