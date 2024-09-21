This project focuses on leveraging MySQL for disk-based analysis. I will import a large dataset into a MySQL database and conduct a series of queries to extract meaningful insights.

# Objectives

- Import the data into a MySQL database
- Analysis using simple queries
- Analysis using complex queries

# Dataset

The dataset is a subset of the Stack Overflow data dump from 2008 to 2010. I have already imported the data into a MySQL database.


# Becoming Familair with the Data

For the first part of the project,familiarize yourself with the schema of the dataset. For each of the questions below, provided the query that used to answer the question along with a description of the query.

- How many questions are in the subset of the data?
- How many answers are in the subset of the data?
- What is the most popular tag in the subset of the data?
- What is the average reputation of users in the subset of the data?
- How many unanswered questions are in the subset of the data?

# Analysis

For the second part of the project, conducted a series of analyses using the dataset. For each of the questions below, provided the query that used to answer the question along with a description of the query. Also provided a visualization of the results where applicable.

## Questions and Answers

Many users come to StackOverflow to get help on their programming questions. Fewer users come to the site to answer questions. In this section, I analyzed the questions and answers in the subset of the data to answer the question: **What percentage of users are actively answering questions versus asking them?**

There are many valid ways to answer this question. solution to this should include three core parts.

1. define what it means to be an "active" user.
2. provided a query that returns the number of active users and the total number of users in the subset.
3. provided a visualization that shows the percentage of active users versus total users.

## Popularity of Tags over Time

Trends come and go in the programming world. In this section, I analyzed the popularity of tags over time to answer the question: **What are the most popular tags over time?** Since the dataset only spans 2 years, aggregated the data by month. Provided a visualization that shows the popularity of tags over time.

1. What are the most popular tags for each month (this should provide you with 24 data points)?
2. Visualize the tags over time using a plot.

## User Reputation Growth

In this section, I analyzed the growth of user reputation to answer the question: **What are the top 10 users that experience the fastest growth in reputation?** I defined time frame to determine growth rate.

## Hot Questions

In this section I provided answers to the following questions.

1. What are the top 20 questions that have the most answers?
2. Of those top 20, how many answers were provided by users in your subset?
3. How do the tags associated with the top 20 questions compare to the most popular tags?