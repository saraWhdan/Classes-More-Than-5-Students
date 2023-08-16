
# Classes More Than 5 Students - LeetCode Problem


Problem Link: [Classes More Than 5 Students](https://leetcode.com/problems/classes-more-than-5-students/)

## Solution


```sql
SELECT class
FROM Courses
GROUP BY class
HAVING COUNT(*) >= 5;
