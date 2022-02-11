# Catch Me If You Can ("Alice")
## Intruder Detection through Webpage Session Tracking

*Web-user identification is a hot research topic on the brink of sequential pattern mining and behavioral psychology.*

*Here we try to identify a user on the Internet tracking his/her sequence of attended Web pages. The algorithm to be built will take a webpage session (a sequence of webpages attended consequently by the same person) and predict whether it belongs to Alice or somebody else.*

*The data comes from Blaise Pascal University proxy servers. Paper "A Tool for Classification of Sequential Data" by Giacomo Kahn, Yannick Loiseau and Olivier Raynaud.*

This is my attempt at solving [this](https://www.kaggle.com/c/catch-me-if-you-can-intruder-detection-through-webpage-session-tracking2/overview) Kaggle competition. 
I achieved a score of 0.96663 ROC-AUC (26th place at the time of publication).
The approach is rather standard and similar to other open Kaggle notebooks: take a bag of words model and apply a linear model on sparse features.
However, by feature engineering and correcting the irreguarities in the dataset I achieved better than average results.
