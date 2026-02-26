## Devesh Singh Chauhan
### I23MA002

## Dataset
- **Amazon Reviews Dataset**: [Link](https://www.kaggle.com/datasets/kritanjalijain/amazon-reviews/data)
- **Google Word2Vec Model**: [Link](https://huggingface.co/fse/word2vec-google-news-300)
- **Word2Vec Tutorial**: [Link](https://www.kaggle.com/code/pierremegret/gensim-word2vec-tutorial)

---

## Assignment Questions

### Q1. Text Preprocessing and Sentence Representation
Load the review column of the dataset and apply the following necessary preprocessing:
- Converting to lowercase
- Removing punctuation and numbers
- Tokenizing text
- Removing stopwords

Find the representation of each sentence using the word vectors of the words.

---

### Q2. Word Analogy Task

#### Part A: Basic Analogies
Consider the analogy examples and find the closest possible word:
- a) good − bad + excellent = ?
- b) delivery − late + fast = ?

#### Part B: Comprehensive Analogy Testing
Take the analogy dataset from: [questions-words.txt](https://github.com/nicholas-leonard/word2vec/blob/master/questions-words.txt)

Check whether you get the correct analogy or not as shown in the above examples.

The word analogy task contains a collection of samples where each sample contains 4 words as:  
**w1 w2 w3 w4**

You need to test: **w2 - w1 + w3 = w4**

As Google Word2Vec model contains around 3 million words, the search space for this task is very high.  
**Question:** How can you minimize the search and get the answer?

---

## Implementation Notes
- Use Gensim library for Word2Vec operations
- Handle out-of-vocabulary words appropriately
- Document the preprocessing steps clearly
- For Q2, discuss optimization strategies for large vocabulary search
