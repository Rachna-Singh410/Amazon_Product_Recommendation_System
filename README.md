# Amazon_Product_Recommendation_System
In current time everything is available online. We can also do shopping online from many online shopping apps i.e. Amazon, Flipkart and Myntra etc. So finding the right product become difficult, to resolve this problem every company like these which are mentioned above use a recommendation system for their customer.

Here we made Amazon Product Recommendation System using K Nearest Neighbor which is a supervised learning algorithm of machine learning algorithm. In this first I read data set and select the product which have more than 50 reviews. Then made a group of all the summary of reviews by product id. After this I made data frame with some columns and then I used KNN classifier to find similar products and predict the result with k=3. It is item-based collaborative filtering model.

### Prerequisites
Some python libraries
```
numpy
nltk
pandas etc.
```
### Installing
```
pip install library_name
```
### Dataset
I took dataset from http://snap.stanford.edu/data/web-Amazon.html. In this dataset columns are id, product id, profile name, score, summary,text.
