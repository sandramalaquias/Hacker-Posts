# Hacker-Posts

In this project, we'll work with a data set of submissions to popular technology site Hacker News.

![Hacker News Posts](https://github.com/sandramalaquias/Hacker-Posts/blob/master/hac1.png)



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

    Do Ask HN or Show HN receive more points on average?

    Do posts created at a certain time receive more points on average?


#### about posts

    Do Ask HN or Show HN receive more posts on average?

    Do posts created at a certain time receive more posts on average?

I divided this project in the following parts, one complemented with other one:
   * analyse files for comments
   * analyse files for points
   * analyse files for posts
   

## GOALS
   * Work with Datetime library
   * work only Python command

## Results 

#### To "Comments"

**Do Ask HN or Show HN receive more comments on average?**
> * Avg Ask HN Coments= 0.67
> * Avg Show HN Coments= 0.33

> On average we can consider that people tend to participate more in "Ask HN" subjects than in "Show HN". Maybe "Show HN" is about a kind of author's contribuition and does not necessarily need a comment.

**Do posts created at a certain time receive more comments on average?**
> * At 15:00 has 38.59% average comments per post.
> * At 02:00 has 23.81% average comments per post
> * At 20:00 has 21.52% average comments per post
> * At 16:00 has 16.80% average comments per post
> * At 21:00 has 16.01% average comments per post

#### To "Points"

**Do Ask HN or Show HN receive more points on average?**
> * Avg Ask Points= 0.45
> * Avg Show Points= 0.55>

> On average we can consider that don't have so many difference between Show and ASK HN. Unlike the previous one, the posts on author's contribuition tend to receive more points.

**Do posts created at a certain time receive more points on average?**
>* At 23:00 has 42.39% average points per post
>* At 12:00 has 41.69% average points per post
>* At 22:00 has 40.35% average points per post
>* At 00:00 has 37.84% average points per post
>* At 18:00 has 36.31% average points per post

#### To "Posts"

**Do Ask HN or Show HN receive more posts on average?**
> * Avg Ask Posts = 0.60
> * Avg Show Posts = 0.40 

> On average, ASK HN has more posts that Show Posts, what make sense.

**Do posts created at a certain time receive more posts on average?** 
>* At 17:00 has 6.78% avarage posts
>* At 16:00 has 6.48% avarage posts
>* At 18:00 has 6.24% avarage posts
>* At 15:00 has 6.14% avarage posts
>* At 14:00 has 5.73% avarage posts

>Don't have so many percent difference along hours.

