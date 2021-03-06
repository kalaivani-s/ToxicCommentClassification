# Toxic Comment Classification

The [Conversation AI team](https://conversationai.github.io/) hosted the [Toxic comment classification challenge](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge) to make online conversations better. One aspect of it involves identifying toxic comments that are rude, disrespectful or obscene. This challenge involves identifying different categories of toxic comments, i.e. toxic, severely toxic, obscene, threat, insult or identity hate. Each comment can be attributed to more than one of these categories. In this notebook, we will try to interpret the aspects that machine learning models use to determine different toxic categories. Hence, we will use classic but interpretable techniques like linear SVM / random forests with TFIDF vector representations. The performance obtained is slightly below the [leading approaches submitted on Kaggle](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/leaderboard) but the motivation here is to understand what drives these machine learning models to classify certain comments as toxic.

The data can be found [here](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data).

The salient features for different toxic categories are as below:

![alt text](https://github.com/kalaivani-s/ToxicCommentClassification/blob/master/salient_features.png "Salient features")
