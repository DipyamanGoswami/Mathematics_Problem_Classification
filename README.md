# Mathematics_Problem_Classification

This project is a part of a Kaggle Competition organized by Bytelearn. As a part of this competition, I was supposed to create a classifier model that would classify
any given mathematical problem to the respective class. I used Sentence-Transformer pretrained model which is 'all-mpnet-base-v2' being one of their best models. I used spaCy for lemmatization and removal of stopwords to extract the tokens. These tokens were then encoded to create the word vector which was then fed to the KNN classifier model for training and prediction. I achieved a public score of 0.66129 and a private score of 0.80952.
