# Bangla_Text_Classification_Utilizing_CNN_with_Bi-LSTM

This project is presented a binary classification of sentiment on a dataset that contains annotated Bangla texts. A deep learning-based hybrid network with CNN with LSTM is used. This classification model presents the text as either positive or negative. In this model, a dataset on Bangla news comments, consisting of Bangla posts for developing a deep learning model is used.

## Table of Contents

(1) **Libraries**

(2) **Dataset**

(3) **Preprocessing**

(4) **Architecture**

(5) **Result** 

(6) **Conclusion**

### Libraries

- [x] **Keras**

- [x] **TensorFlow**

- [x] **Scikit-Learn**

### Dataset

- _[predicted_unsupervised_sentiment.xlsx](https://github.com/OviSarkar62/Bangla_Text_Classification_Utilizing_CNN_with_Bi-LSTM/blob/0b4fd2469c2b4e42fa56d8c6ac2ba097fb88297f/predicted_unsupervised_sentiment.xlsx)_

### Preprocessing

- The dataset contains many unwanted things (Punctuations,English words,emojis etc..).I have cleaned this things with pre-defined function.
- Converted all sentences into a numpy Array.
- Converted the sentiment values into one hot encodings for the convenient use in model training.
- Done tokenization so that it can be later used to generate Embeddings.
- Padded the sequences.
