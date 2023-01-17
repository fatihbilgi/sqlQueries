#### 1) The data in the title and description columns in the film table.
`SELECT title, description FROM film;`

#### 2) The data in all columns in the film table whose film length is greater than 60 AND less than 75.
`SELECT * FROM film WHERE length > 60 AND length < 75;`

#### 3) The data in all columns in the film table whose rental_rate 0.99 and replacement_cost 12.99 or replacement_cost 28.99.
`SELECT * FROM film WHERE rental_rate = 0.99 AND replacement_cost = 12.99 OR replacement_cost = 28.99;`

#### 4) What is the value in the last_name column of the customer whose value in the first_name column in the customer table is 'Mary'?
`SELECT first_name, last_name FROM customer Where first_name = 'Mary';`

#### 5) The data in the film table whose length is NOT greater than 50 and at the same time the rental_rate value is NOT 2.99 or 4.99.
`SELECT * FROM film WHERE NOT length > 50 AND NOT(rental_rate = 2.99 OR rental_rate = 4.99);`
