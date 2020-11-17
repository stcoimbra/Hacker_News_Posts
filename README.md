## Hacker news - Post Anlaysis
In this project, we'll compare two different types of posts from [Hacker News](https://news.ycombinator.com/), a popular site where technology related stories (or 'posts') are voted and commented upon. The two types of posts we'll explore begin with either **Ask HN** or **Show HN**.

Users submit **Ask HN** posts to ask the Hacker News community a specific question, such as "What is the best online course you've ever taken?" Likewise, users submit **Show HN** posts to show the Hacker News community a project, product, or just generally something interesting.

We'll specifically compare these two types of posts to determine the following:

- Do Ask HN or Show HN receive more comments on average?
- Do posts created at a certain time receive more comments on average?
It should be noted that the data set we're working with was reduced from almost 300,000 rows to approximately 20,000 rows by removing all submissions that did not receive any comments, and then randomly sampling from the remaining submissions.

---
### What the data set is in this project
Resourse: https://www.kaggle.com/hacker-news/hacker-news-posts

This data set is Hacker News posts from September 2015 to September 2016

It includes the following columns:

- **title:** title of the post (self explanatory)
- **url:** the url of the item being linked to
- **num_points:** the number of upvotes the post received
- **num_comments:** the number of comments the post received
- **author:** the name of the account that made the post
- **created_at:** the date and time the post was made (the time zone is Eastern Time in the US)
---

### In this project it was used:
- List and for loops
- Conditional statements
- Dictionaries and frequency tables
- Functions
- Datetime format, aggregations, and comparisons
- Jupyter Notebook

---
This project is inspired by the final challenge of the course [Python for Data Science: Intermediate Course](https://app.dataquest.io/course/python-for-data-science-intermediate), inserted in the [Data Scientist in Python](https://app.dataquest.io/path/data-scientist) path


**Certificate of Completion:** https://app.dataquest.io/verify_cert/P9B7HM30KBZ3H4VU27GJ/
