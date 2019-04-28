---
title: "Introduction: building a database system from scratch"
date: 2019-05-28T00:00:00+00:00
draft: false
---

Database systems are ubiquitous and every developer will use one at some point. Despite their widespread use, few developers seem to have a clean conceptual model of how they work and have only limited knowledge on to make the best use of them. I am certainly one of them.

In order to fix that, I want to see if it is possible to build a simple, yet realistic, database system from scratch. Although there are many resources in the internet (see list below), I couldn't find a book doing just that: building from the ground up with the actual code and not too much theory. Sure I could jump to look at the source code of Sqllite or PostgreSQL, but the key elements would be lost in all the features. How would I understand the key tradeoffs and design decisions? 

Ideally, this should start from the basic I/O operation from the operating system and go up to running SQL queries, with concurrency and transaction support. It should be developed cleanly, with lots of tests and benchmarking.

I don't know yet how much work this will take, but I am planning to find out and describe this in this blog. The source code will also be open-sourced.

In the next post, I'll describe in more details the scope of what I will build.