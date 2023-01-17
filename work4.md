#### 1) List the unique values in the replacement_cost column in the film table.
`SELECT DISTINCT replacement_cost FROM film;`

#### 2) The number of unique data in the replacement_cost column in the film table.
`SELECT COUNT(DISTINCT replacement_cost) FROM film;`

#### 3) The number of data from the title column in the film table that starts with the character T and has a rating equal to 'G'.
`SELECT COUNT(*) FROM film WHERE title LIKE 'T%' AND rating = 'G';`

#### 4) The number of countries in the country table with country names consisting of 5 characters.
`SELECT COUNT(*) FROM country WHERE country LIKE '_____';`

#### 5) The number of city names in the city table ending in 'R' or 'r'.
`SELECT COUNT(*) FROM city WHERE city ILIKE '%r';`
