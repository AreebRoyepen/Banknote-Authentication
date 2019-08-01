# Banknote-Authentication
Machine Learning Group Project

This project involves trying to detect whether or not a given note is forged (y=1) or genuine (y=0). The data set contains information extracted from very high-resolution images that were taken from genuine and forged banknote-like specimens. An industrial camera usually used for print inspection was used. After digitizing the notes, a specific algorithm was applied to them (a wavelet transform) to extract specific set of aggregate features from the images to make up a total of 4 features that an expert determined could be sufficient to predict whether or not a note was genuine or forged. 

The features are as follows:

1.	Variance of wavelet transformed image
2.	Skewness of wavelet transformed image
3.	Kurtosis of wavelet transformed image
4.	Entropy of the image

Run in order:

group21_divide data
group21_train_logreg
group21_train_SVM
group21_train_nn
group21_test
group21_demo

Areeb Royeppen did the neural network
Keelan Govender did the SVM
Mulayo Tshivase did logistic regression

