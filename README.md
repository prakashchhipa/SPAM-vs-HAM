# SPAM-vs-HAM
Classical machine learning based solution to detect SPAM messages over SMS spam collection dataset available at UCI Machine Learning.

**Problem Statement:**

Classify SPAM messages out of all the SMS

This dataset made available at https://www.kaggle.com/uciml/sms-spam-collection-dataset

**Solution:**

Refer HAMvsSPAM.py


1) Data Loading & Preprocessing - Loaded textual data into Panda DataFrames. Anotated lebels. Performed lower casing, punctuation removel, and stop words deletions
2) Feature Engineering - Created One Hot enncoded form of BOW(Frequenct count) encoding, TF-IDF(term frequency - inverse document frequency) encoding & simply word length feature
3) ML Classifiers - Considered LogisticRegression, KNeighborsClassifier, DecisionTreeClassifier, RandomForestClassifier, SVM, GradientBoostingClassifier & NaiveBayes Bernoulli, and NaiveBayes Gaussian
4) Train/Test & Cross Validation - Considered 70/30 train/test ratios and vaerified with K-Fold Validation (10 & 15 fold)

**Outcome:**
NaiveBayes Bernoulli(F1 score 99%) & Logistic Regression (F1 Score/Accuracy 98.9%) outperfomed out of all classifiers.

**Reasoning behind out performing of NaiveBayes(Bernoulli): It seems better representation for features distribution being in modeled as binary type data under the hood of Bernoulli Distribution due to one hote encoded format for all the features.**

**Execution Environment & Required Library:**

 1. Python 3.x
 2. Libraries
    - Scikit Learn
    - NLTK
    - Numpy
    - Pandas
    - Matplotlib
    - Scipy
    - Seaborn


**Note for other Enthusiastic contributor:**

Most welcome to extend this experiment with better feature engineering by considering learning based embedding techniques and utilizing Neural Network based classfier models.

**Queries?...Connect with me at:**

LinkedIn: https://linkedin.com/in/prakash-chandra-chhipa

Email: prakash.chandra.chhipa@gmail.com
