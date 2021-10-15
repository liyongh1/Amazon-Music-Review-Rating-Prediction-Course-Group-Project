# Amazon Music Review Rating Prediction (NLP, NLTK, Kaggle in-class competition)

- Designed pipeline to tokenize, remove stop-words, and lemmatize about 500,000 samples of Amazon Music review text data using RegEx and NLTK library, before feeding the training portion into TF-IDF;

- Developed an XGBoost Regressor and a Multilayer Perceptron using Scikit-learn by fitting the sparse data which came with unbalanced class distribution. Tuned model performance using adaptive learning rate and ReLU activation function to predict review scores (1-5) produced by users in the test set;

- Achieved best resulting MSE around 0.46, putting the team in the top 20% of the in-class Kaggle competition.
