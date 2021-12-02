# 0x0C. MySQL advanced

## Requirements

+ All your files will be executed on Ubuntu 18.04 LTS using `MySQL 5.7` (version 5.7.30)
+ All your files should end with a new line
+ All your SQL queries should have a comment just before (i.e. syntax above)
+ All your files should start by a comment describing the task
+ All SQL keywords should be in uppercase (`SELECT`, `WHERE…`)
+ A `README.md` file, at the root of the folder of the project, is mandatory
+ The length of your files will be tested using `wc`

### Comments for your SQL file

```sql
$ cat my_script.sql
-- 3 first students in the Batch ID=3
-- because Batch 3 is the best!
SELECT id, name FROM students WHERE batch_id = 3 ORDER BY created_at DESC LIMIT 3;
$
```

### How to import a SQL dump

```sql
$ echo "CREATE DATABASE hbtn_0d_tvshows;" | mysql -uroot -p
Enter password: 
$ curl "https://s3.amazonaws.com/intranet-projects-files/holbertonschool-higher-level_programming+/274/hbtn_0d_tvshows.sql" -s | mysql -uroot -p hbtn_0d_tvshows
Enter password: 
$ echo "SELECT * FROM tv_genres" | mysql -uroot -p hbtn_0d_tvshows
Enter password: 
id  name
1   Drama
2   Mystery
3   Adventure
4   Fantasy
5   Comedy
6   Crime
7   Suspense
8   Thriller
$
```

## Tasks

0. We are all unique!
1. In and not out
2. Best band ever!
3. Old school band
4. Buy buy buy
5. Email validation to sent
6. Add bonus
7. Average score
8. Optimize simple search
9. Optimize search and score
10. Safe divide
11. No table for a meeting
12. Average weighted score
13. Average weighted score for all!

## AUTHOR

### JACKSON MORENO
