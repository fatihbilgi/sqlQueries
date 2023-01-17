# A-1)
`SELECT rating, COUNT(*) FROM film GROUP BY rating;`

# A-2)
`SELECT replacement_cost, COUNT(*) FROM film GROUP BY replacement_cost HAVING COUNT(*) > 50;`

# A-3)
`SELECT store_id, COUNT(*) FROM customer GROUP BY store_id;`

# A-4)
`SELECT country_id, COUNT(*) FROM city GROUP BY country_id ORDER BY COUNT(*) DESC;`
