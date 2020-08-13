# sparkNLP
Classifier:
This python notebook demosntrate basic steps involved in data cleaning & text processing in sparkNLP followed by classificatioin using sparkML.
It uses song lyrics data from <https://www.kaggle.com/neisse/scrapped-lyrics-from-6-genres> to classify genre of songs based on their lyrics.

Following are the steps involved:
1. Loading Data
2. Text Preprocessing : Tokenizer, spell check, lemmatizer, normalizer, stop word cleaner
3. vectorization: using bag of words & Glove embedding
4. classification:Logistic Regression & Random Forest

Sentiment Analysis:
This python notebook determines top words (word clusters) for both positive and negative sentiments in our document. 
We are using the same lyric-genre dataset. We create two segments based on sentiments (positive and negative) and then find out top words in each of these segments performing topic modeling using TF-IDF and LDA.

Following are the steps involved:
1. Loading Data
2. Text Preprocessing : Tokenizer, spell check, lemmatizer, normalizer, stop word cleaner
3. Sentiment Analysis: using analyze_sentiment (which uses Word2Vec in the backhood) from sparkNLP
4. Topic Modeling:using TF-IDF vectors and classification using LDA


