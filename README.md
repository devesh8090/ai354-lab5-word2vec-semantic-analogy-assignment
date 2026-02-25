# ai354-lab5-word2vec-semantic-analogy-assignment
Devesh Singh Chauhan
I23MA002

Use the dataset: https://www.kaggle.com/datasets/kritanjalijain/amazon-reviews/data
Use the Google Word2Vec model: https://huggingface.co/fse/word2vec-google-news-300
Word2Vec Tutorial: https://www.kaggle.com/code/pierremegret/gensim-word2vec-tutorial

Q1. Load the review column of the dataset and apply the following necessary preprocessing.
- Converting to lowercase
- Removing punctuation and numbers
- Tokenizing text
- Removing stopwords
Find the representation of each sentence using the word vectors of the words
Q2. Consider the analogy examples such as and find the closest possible word
a) good − bad + excellent =
b) delivery − late + fast =
Take the analogy dataset from
https://github.com/nicholas-leonard/word2vec/blob/master/questions-words.txt and check
whether you get the correct analogy or not as shown in the above examples.
The word analogy task contains a collection of samples where each sample contains 4 words as
w1 w2 w3 w4
You need to test w2 - w1 + w3 = w4
As Google word2vec model contains around 3 million words, the search space for this task is
very high. How can you minimize the search and get the answer?
