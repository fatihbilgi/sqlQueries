#### A-1)
```sql
SELECT city, country From city
LEFT JOIN country ON city.country_id = country.country_id;
```

#### A-2)
```sql
SELECT first_name, last_name, payment_id FROM customer
RIGHT JOIN payment ON customer.customer_id = payment.customer_id;
```

#### A-3)
```sql
SELECT rental_id, first_name, last_name FROM customer
FULL JOIN rental ON customer.customer_id = rental.customer_id;
```
