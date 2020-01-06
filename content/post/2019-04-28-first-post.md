---
title: "Introduction"
date: 2019-04-28T00:00:00+00:00
draft: false
---

Database systems are ubiquitous. Every developer will use one at some point. Despite their widespread use, few developers seem to have a clean conceptual model of how they work and have only limited knowledge of how to make the best use of them. I am certainly one of them.

SQL: One of the Most Valuable Skills: http://www.craigkerstiens.com/2019/02/12/sql-most-valuable-skill/

SQL might not be "fancy", but...

You need to know SQL to know when to use it. Most people assume what it is and what it can do for you.

SQL is timeless
Good investment of your time, learn once, use everywhere.

SQL is used everywhere

SQL can do more than you think (basic subqueries to windows functions)

SQL can do more for you than you think (performance, caching, optimization based on actual query and actual database data distribution, parallele processing)
* more optimized execution with dynamic jit and co
* no back and forth with latency at each query
* handle parallele processing for you...(haaard to do)

SQL allows you to write less code

SQL get shits done

SQL can make you more productive (4GL, focus on business logic)

SQL is fast and at least faster than you can do with your code
SQL can be fast with little of effort (can do complex optimization dynamically, more complex that you could do, use cardinality, as a dev you can't even find algo this good in most case or at least will use a lot of time: https://www.youtube.com/watch?v=wTPGW1PNy_Y)

Without indexes, your query will be slow, you need to learn

You should know this things: they are interesting and usefull

Learn to use indexes (yes, its your job as a programmer too)

Many people skip over it or get only a rudimentary self-taught version

https://news.ycombinator.com/item?id=19149792

In order to fix that, I want to see if it is possible to build a simple, yet realistic, database management system from scratch. Although there are many resources in the internet (see list below), I couldn't find a book doing just that: building from the ground up with actual code and not too much theory. Sure I could go to look at the source code of SQLlite or PostgreSQL, but the key elements would be lost in all the features. How would I understand the key tradeoffs and design decisions? 

Ideally, this should start from the basic I/O operation offered by the operating system and go up to running SQL queries, with concurrency and transaction support. It should be developed cleanly, with lots of tests and benchmarking.

I don't know yet how much work this will take, but I am planning to find out and describe everything in this blog. The source code will also be open-sourced.

In the next post, I'll describe in more details the scope of what I will build.

Understanding the logical model to get the correct result

To make best use of SQL, you need a deeper understanding of the physical model.

understanding the physical model to not shoot yourself in the foot with performance

get proficient with SQL

You don't get good at sql by just reading, but by practicing...

https://news.ycombinator.com/item?id=11981045

https://news.ycombinator.com/item?id=19588961
SQL databases come up with algorithms you’d never have dreamed of (2017) [video] (youtube.com)

Ten SQL Tricks that You Didn’t Think Were Possible (Lukas Eder) - https://www.youtube.com/watch?v=mgipNdAgQ3o

I saw what a collegue wrote as SQL and I was shocked as how much I sucked at SQL.

Use example of alien trying to control the universe. The Big GURGUL


Leaner, Faster Code with Advanced SQL Techniques: https://www.youtube.com/watch?v=txeBfKjNRAw


Juste having an index don't insure you that it will be faster