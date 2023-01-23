#### A-1)
```sql
SELECT city, country FROM country
INNER JOIN city ON country.country_id = city.country_id;
```

#### A-2)
```sql
SELECT payment_id, first_name, last_name FROM payment
INNER JOIN customer ON customer.customer_id = payment.customer_id;
```

#### A-3)
```sql
SELECT rental_id, first_name, last_name FROM rental
INNER JOIN customer ON customer.customer_id = rental.customer_id;
```
