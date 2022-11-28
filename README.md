# Data-Analysis-Hacker-News-Post-

## Introduction

Hacker News is a site started by the startup incubator Y Combinator, where user-submitted stories (known as "posts") receive votes and comments, similar to reddit. Hacker News is extremely popular in technology and startup circles, and posts that make it to the top of the Hacker News listings can get hundreds of thousands of visitors as a result.

You can find the data set here, but note that we have reduced from almost 300,000 rows to approximately 20,000 rows by removing all submissions that didn't receive any comments and then randomly sampling from the remaining submissions. Below are descriptions of the columns:

- id: the unique identifier from Hacker News for the post

- title: the title of the post

- url: the URL that the posts links to, if the post has a URL

- num_points: the number of points the post acquired, calculated as the total number of upvotes minus the total number of downvotes

- num_comments: the number of comments on the post

- author: the username of the person who submitted the post

- created_at: the date and time of the post's submission

We're specifically interested in posts with titles that begin with either Ask HN or Show HN.
