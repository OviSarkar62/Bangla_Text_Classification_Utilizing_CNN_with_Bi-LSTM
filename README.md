# Bangla_Text_Classification_Utilizing_CNN_with_Bi-LSTM

This project is presented a binary classification of sentiment on a dataset that contains annotated Bangla texts. A deep learning-based hybrid network with CNN with Bidirectional LSTM is used. This classification model presents the text as either positive or negative. In this model, a dataset on Bangla news comments, consisting of Bangla posts for developing a deep learning model is used.

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

<p align="center">
  <img alt="img-name" src="Images/Tokenization and Padding.png" width="500">
  <br>
    <em>Fig: Tokenization and Padding</em>
</p>

### Architecture

<p align="center">
  <img alt="img-name" src="Images/Model Architecture.png" width="400">
  <br>
    <em>Fig: Model Architecture</em>
</p>

### Results

- **Train & Test Accuracy**
<p align="center">
  <img alt="img-name" src="Images/Train and Test Accuracy.png" width="600">
  <br>
    <em>Fig: Train and Test Accuracy</em>
</p>

- **Learning Curve**
<p align="center">
  <img alt="img-name" src="Images/Model Accuracy.png" width="400">
  <br>
    <em>Fig: Model Accuracy</em>
</p>

<p align="center">
  <img alt="img-name" src="Images/Model Loss.png" width="400">
  <br>
    <em>Fig: Model Loss</em>
</p>

### Conclusion

This project is focused on a particular deep neural network model for the effective implementation of Bangla language sentiment. All Bangla sentences in this model have been classified into two categories from the dataset. Additionally, the accuracy of the model is much more than other models. 

---
### Author's Info
- **LinkedIn: [ovisarkar1610052](https://www.linkedin.com/in/ovisarkar1610052/)**
- **ResearchGate: [Ovi Sarkar](https://www.researchgate.net/profile/Ovi-Sarkar)**
---
