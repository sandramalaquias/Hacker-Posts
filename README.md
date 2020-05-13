# Hacker-Posts

In this project, we'll work with a data set of submissions to popular technology site Hacker News.

![image.png](attachment:image.png)



Hacker News is a site started by the startup incubator Y Combinator, where user-submitted stories (known as "posts") are voted and commented upon, similar to reddit. Hacker News is extremely popular in technology and startup circles, and posts that make it to the top of Hacker News' listings can get hundreds of thousands of visitors as a result.

You can find the data set here, but note that it has been reduced from almost 300,000 rows to approximately 20,000 rows by removing all submissions that did not receive any comments, and then randomly sampling from the remaining submissions. Below are descriptions of the column:

    * id: The unique identifier from Hacker News for the post
    * title: 
    * url: The URL that the posts links to, if it the post has a URL
    * num_points: The number of points the post acquired, calculated as the total number of upvotes minus the total number of downvotes
    * num_comments: The number of comments that were made on the post
    * author: The username of the person who submitted the post
    * created_at: The date and time at which the post was submitted

We're specifically interested in posts whose titles begin with either Ask HN or Show HN. Users submit Ask HN posts to ask the Hacker News community a specific question. Below are a couple examples:

    Ask HN: How to improve my personal website? 
     Ask HN: Am I the only one outraged by Twitter shutting down share counts? 
    Ask HN: Aby recent changes to CSS that broke mobile?


Likewise, users submit Show HN posts to show the Hacker News community a project, product, or just generally something interesting. Below are a couple of examples:

    Show HN: Wio Link  ESP8266 Based Web of Things Hardware Development Platform'
    Show HN: Something pointless I made
    Show HN: Shanhu.io, a programming playground powered by e8vm
    
We'll compare these two types of posts to determine the following:

#### about comments

    Do Ask HN or Show HN receive more comments on average?
    Do posts created at a certain time receive more comments on average?


#### about points

    Do Ask HN or Show HN receive more points on average?___

    Do posts created at a certain time receive more points on average?


#### about posts

    Do Ask HN or Show HN receive more posts on average?___

    Do posts created at a certain time receive more posts on average?




