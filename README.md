# Toxic-Comment-Classification-Challenge-Kaggle

Kaggle Toxic Comment Classification Challenge: (https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge) <br />
<br />
Single LSTM + GRU Model with 10 fold CV yields a ROC-AUC score of 0.9871 against public LB highest of 0.9890 with current soultion ranked 300th on public LB <br />
<br />
**Further Details:** <br />
Embeddings - fastText & GloVe Twitter (200d) <br />
Implementation Libraries - Pytorch (Model) & Keras (Text Pre-processing) <br />
<br />
**Scope for Improvement:** <br />
1. Modifying model architecture with focus on better regularization
2. Ensembling different baseline models (though ensembling with NB-SVM baseline did not help improve the score) <br />
<br />
<br />
**Note:**
Did not use BERT baseline since it wasn't released at the time of competition <br />
