# Book-Recommendation-system
A recommendation system is one of the top applications of data science. Every consumer Internet company requires a recommendation system like Netflix, Youtube, a news feed, etc. What you want to show out of a huge range of items is a recommendation system.​

Project of Contents
​

1. Introduction to a Recommendation system​
2. Types of Recommendation system​
3. Book Recommendation System
Popularity Based Recommender System
Content-Based Filtering
Collaborative-based filtering
Hybrid filtering​
4. Hands-on Recommendation system
Dataset Description
Preprocess data
Perform EDA
Clustering
Predictions
Book Recommendation System
A book recommendation system is a type of recommendation system where we have to recommend similar books to the reader based on his interest. The books recommendation system is used by online websites which provide ebooks like google play books, open library, good Read’s, etc.​In this article, we will use the Collaborative based filtering method to build a book recommender system. You can download the dataset from here​​Practical Implementation of Recommendation System​Let’s make our hands dirty while trying to implement a Book recommendation system using collaborative filtering.​Dataset Description

we have 3 files in our dataset which is extracted from some books selling websites.​
Books – first are about books which contain all the information related to books like an author, title, publication year, etc.​
Users – The second file contains registered user’s information like user id, location.​
ratings – Ratings contain information like which user has given how much rating to which book.
So based on all these three files we can build a powerful collaborative filtering model. let’s get started.
