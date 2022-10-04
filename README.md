# 100 Days of SQL
Practicing SQL, one day at a time.

Here are the notes I'm taking along the way.

### Day 1

I'll start by following *Practical SQL* by Anthony DeBarros.

![](./img/practical_sql.jpeg)



I've installed PostgreSQL and Azure Data Studio. I use VS Code daily, so I like the familiarity of Azure Data Studio as an IDE.

* create a database using `CREATE DATABASE analysis;`
* `bigserial` - integer type that auto-increments each time a new row is added to table. e.g.

```sql
CREATE TABLE teachers (
    id bigserial,
    first_name varchar(25),
    last_name varchar(50),
    school varchar(50),
    hire_date date,
    salary numeric
);
```

