#### A-1)
```sql
(SELECT first_name FROM actor)
UNION
(SELECT first_name FROM customer);
```

#### A-2)
```sql
(SELECT first_name FROM actor)
INTERSECT
(SELECT first_name FROM customer);
```

#### A-3)
```sql
(SELECT first_name FROM actor)
EXCEPT
(SELECT first_name FROM customer);
```
