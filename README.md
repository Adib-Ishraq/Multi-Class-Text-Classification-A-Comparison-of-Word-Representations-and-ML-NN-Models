This project applies a comprehensive experimental
 pipeline to a multi-class question-answer topic classification
 dataset. We performed exploratory data analysis (EDA), applied
 standard text preprocessing, implemented four word representa
tions (Bag-of-Words, TF-IDF, GloVe, Skip-gram), and trained a
 suite of models: three classic machine learning classifiers (Logistic
 Regression, Naive Bayes, Random Forest) and seven neural
 network architectures (DNN, SimpleRNN, GRU, LSTM, and their
 bidirectional variants). We trained the ML models on BoW,TF
IDF; all NN architectures on GloVe,Skip-gram with and DNN
 on all four. The best ML model found was Logistic Regression
 with TF-IDF and the best NN model was a Bidirectional GRU
 with Skip-gram embeddings.
