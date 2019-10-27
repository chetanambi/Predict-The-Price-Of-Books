# Predict-The-Price-Of-Books
![image](https://user-images.githubusercontent.com/37707687/67630550-693bc200-f8af-11e9-87a5-f6948a9a0eb5.png)

The so-called paradoxes of an author, to which a reader takes exception, often exist not in the author’s book at all, but rather in the reader’s head. – Friedrich Nietzsche

Books are open doors to the unimagined worlds which is unique to every person. It is more than just a hobby for many. There are many among us who prefer to spend more time with books than anything else.

Here we explore a big database of books. Books of different genres, from thousands of authors. In this challenge, participants are required to use the dataset to build a Machine Learning model to predict the price of books based on a given set of features.

Size of training set: 6237 records
Size of test set: 1560 records

## FEATURES:
Title: The title of the book
Author: The author(s) of the book.
Edition: The edition of the book eg (Paperback,– Import, 26 Apr 2018)
Reviews: The customer reviews about the book
Ratings: The customer ratings of the book
Synopsis: The synopsis of the book
Genre: The genre the book belongs to
BookCategory: The department the book is usually available at.
Price: The price of the book (Target variable)

## Metric
Submissions are evaluated on Root-Mean-Squared-Error (RMSE) between the predicted value and observed score values. The final score calculation is done in the following way:

Submissions are evaluated on Root-Mean-Squared-Log-Error (RMSLE) error = RMSLE (error)

Score = 1 – error

## Leaderboard
Rank 6 (Score: 0.791311) 
