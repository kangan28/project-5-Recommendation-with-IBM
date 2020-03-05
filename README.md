# Project5-Recommendations-with-IBM

In this project I have analyzed the interactions that users have with articles on the IBM-Watson-Studio-platform and thus making recommendations to them about new articles I think they will like.

My project is divided into the following tasks:

I. Exploratory Data Analysis

Finding out distribution of articles a user interact within the dataset and thereby providing visual and descriptive statistics.

II. Rank Based Recommendations

Providing functions to get n top articles names and n top articles ids.

III. User-User Based Collaborative Filtering Function create_user_item_matrix: reformating the df dataframe to be shaped with users as rows and articles as columns.
Each user should only appear in each row once. Each article should only show up in one column. 
If a user has interacted with an article, then place a 1 where the user-row meets for that article-column. It does not matter how many times a user has interacted with the article, all entries where a user has interacted with an article should be a 1.
If a user has not interacted with an item, then place a zero where the user-row meets for that article-column

IV. Matrix Factorization: Building matrix factorization to make article recommendations to users on the IBM Watson Studio platform
