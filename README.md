# Advanced SQL for Query Tuning and Performance Optimization
This is the repository for the LinkedIn Learning course Advanced SQL for Query Tuning and Performance Optimization. The full course is available from [LinkedIn Learning][lil-course-url].

![Advanced SQL for Query Tuning and Performance Optimization][lil-thumbnail-url] 

SQL queries can be fast and highly efficient, but they can also be slow and demand excessive CPU and memory resources. For many SQL programmers, occasional bouts with long-running queries and poor performance are simply par for the course. But by gaining a better understanding of how databases translate SQL queries into execution plans, you can take steps to avoid these issues. In this course, Dan Sullivan shows you how to analyze query execution plans and use data modeling strategies to boost query performance. Dan describes how SQL queries are executed, highlights different types of indexes and how they factor in query tuning, covers several methods for performing joins, and discusses how to use partitioning and materialized views to improve performance. Plus, Dan shows you how to run PostgreSQL in GitHub Codespaces so you can get started learning faster.

## Instructions
This repository has branches for each of the videos in the course. You can use the branch pop up menu in github to switch to a specific branch and take a look at the course at that stage, or you can add `/tree/BRANCH_NAME` to the URL to go to the branch you want to access.

## Branches
The branches are structured to correspond to the videos in the course. The naming convention is `CHAPTER#_MOVIE#`. As an example, the branch named `02_03` corresponds to the second chapter and the third video in that chapter. 
Some branches will have a beginning and an end state. These are marked with the letters `b` for "beginning" and `e` for "end". The `b` branch contains the code as it is at the beginning of the movie. The `e` branch contains the code as it is at the end of the movie. The `main` branch holds the final state of the code when in the course.

When switching from one exercise files branch to the next after making changes to the files, you may get a message like this:

    error: Your local changes to the following files would be overwritten by checkout:        [files]
    Please commit your changes or stash them before you switch branches.
    Aborting

To resolve this issue:
	
    Add changes to git using this command: git add .
	Commit changes using this command: git commit -m "some message"

## Installing
Clone this repository into your local machine using the terminal (Mac), CMD (Windows), or a GUI tool like SourceTree.

### Instructor

Dan Sullivan 
                            


Check out my other courses on [LinkedIn Learning](https://www.linkedin.com/learning/instructors/dan-sullivan).

[lil-course-url]: https://www.linkedin.com/learning/advanced-sql-for-query-tuning-and-performance-optimization-22891253?dApp=59033956&leis=LAA
[lil-thumbnail-url]: https://media.licdn.com/dms/image/D560DAQHhgQSU6L_R7w/learning-public-crop_675_1200/0/1697652769241?e=2147483647&v=beta&t=K_grEUNxvoxg2011Gu7QVV3AyEFM3PxXr1r7DQUoSbc


