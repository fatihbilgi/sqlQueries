#### A-1)
```sql
Select Count(title) From film
Where length >
(
	Select AVG(length) From film
);
```

#### A-2)
```sql
Select Count(title) From film
Where rental_rate = (Select MAX(rental_rate) From film);
```

#### A-3)
```sql
Select title, rental_rate, replacement_cost From film
Where rental_rate = 
(Select MIN(rental_rate) from film) 
and 
replacement_cost = (Select MIN(replacement_cost) from film);
```

#### A-4)
```sql
SELECT customer.first_name, customer.last_name FROM payment
INNER JOIN customer ON payment.customer_id = customer.customer_id
WHERE payment.amount =
(
    SELECT MAX(amount) FROM payment
);
```
