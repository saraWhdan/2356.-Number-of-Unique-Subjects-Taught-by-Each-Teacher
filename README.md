# 2356. Number of Unique Subjects Taught by Each Teacher
### Problem Link & Description :[ Number of Unique Subjects Taught by Each Teacher](https://leetcode.com/problems/number-of-unique-subjects-taught-by-each-teacher/description/?envType=study-plan-v2&envId=top-sql-50)
## Solution 
```sql
/* Write your T-SQL query statement below */

SELECT teacher_id
,COUNT(DISTINCT subject_id) cnt
FROM Teacher 
GROUP BY teacher_id

