
# Classes More Than 5 Students - LeetCode Problem

## Problem Description

You are given a table named `Courses`, with columns `student` and `class`. The `Courses` table contains information about students and the classes they are attending.

Your task is to write an SQL query that finds all the classes that have at least five students.

Problem Link: [Classes More Than 5 Students](https://leetcode.com/problems/classes-more-than-5-students/)

## Solution

To find all the classes that have at least five students, you can use the following SQL query:

```sql
SELECT class
FROM Courses
GROUP BY class
HAVING COUNT(*) >= 5;
