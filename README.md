# Fake News Filter - Machine Learning Project

This is a project I made in late 2020 for a Machine Learning class. The project was to solve some problem with some data using various models, and to perform analysis on the dataset. I found a database that compiled 45000 fake and true news stories and tried to create models to classify which category some story belongs to. The features used were the text of the articles, and I used the Natural Language Toolkit library to perform lemmatization and stopword removal on the words. I used the NumPy and Pandas libraries to create matrices, as well as the Matplotlib library to graph results.

I first performed unsupervised analysis on the data using the k-means algorithm. I then attempted to create models using a variety of hyperparameter values and different settings for Logistic Regression, Support Vector Machines, and Neural Networks. I finally performed some feature transformation by decreasing the number of features and testing how the performance changes for the best performing models in each category.

Attached in this repository are the Jupyter notebook file, the writeup for the project, a spreadsheet of my results, and the data I used in the form of two CSV files. If you want to know more about how the project was conducted, the writeup goes into a great amount of detail.
