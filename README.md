![nns](./img/nns.jpg)

This is my final project for the SJTU Bioinformatics class. We were asked to do data analysis on microarray gene expression data; however most traditional machine learning methods fail with this data set because n << p. For example, PCA is a terrible approximation to the real covariance of the data, most neural network architectures overfit, etc. In these cases, a sparsity assumption is usually made, and we show how applying sparse PLSDA and Deep Learning we can build robust classifiers.

I will not go into all the details, but we built a classifier that was 100% accurate in classifying all 5 major different types of leukemia; the reader can have a look at the slides or the report for an in-depth explanation. 

Here is a picture of the leukemia dataset visualised transformed in to the sPLSDA feature space:

![plsda_classes](./img/plsda_classes.jpg)