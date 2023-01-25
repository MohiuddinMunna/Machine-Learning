This machine learning project is 'Sentiment Analysis of Comments in Social Media' based on NLP.
In this project, we evaluates a sentiment analysis study that was conducted on 999 Facebook posts and 162980 tweets, which were then combined and further processed.
This study included several enhancement methods, including feature extraction, classification algorithms, NLP techniques, and more, including the ability to recognize polarity.
For sentiment analysis, we gathered and manually categorized a sizable dataset from twitter and Facebook comments. This dataset we collected from Kaggle and preprocess by own way. This dataset includes thoughts from viewers about various English comments and postings. As we are interested in Social media sentiment data we collected data based on negative, positive and another is neutral.
At first we selected important and common features from both dataset then changed column name on both dataset. Then we replaced all punctuation mark with null and deleted all duplicated comments. Then we merged both cleaned dataset into one and splits into train and test data. At last we vectored data to convert text data to numerical data to understand machine. At preprocessing i also applied tf-idf vectorizer(convert text data into numerical data),Tokenizer(split sentence into smaller units),pad_sequence(used to ensure that all sequences in a list have the same length).
Here, we apply the ML algorithms SVM, DT, XGBoost, and deep learning-based algorithm LSTM. 5.SVM-93% accuracy, DT-82% accuracy, XGBoost-71% accuracy, LSTM-90% accuracy.
