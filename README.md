# test
1) SELECT * FROM actor;
2) SELECT * FROM actor WHERE (first_name = 'John');
3) SELECT * FROM actor WHERE (last_name = 'Neeson');
4) SELECT * FROM actor WHERE (actor_id mod 10 = 0);
5) SELECT description FROM film WHERE (film_id = '100');
6) SELECT * FROM film WHERE (rating = 'R');
7) SELECT * FROM film WHERE (rating != 'R');
8) SELECT * FROM film ORDER BY length ASC LIMIT 10;
9) SELECT title FROM film ORDER BY length ASC LIMIT 10;
10) SELECT * FROM film WHERE (special_features = 'Deleted Scenes');
11) SELECT DISTINCT last_name from actor;
12) SELECT last_name FROM actor GROUP BY last_name;
13)
14)
15) SELECT release_year FROM film WHERE title = 'Academy Dinosaur';
16) SELECT AVG(length) FROM film;
17) SELECT category, AVG(length) FROM film_list GROUP BY category;
18) SELECT COUNT(*) FROM film WHERE (description LIKE '%robot%');
19) SELECT title, length FROM film WHERE length = (SELECT MAX(length) FROM film);
20) SELECT COUNT(*) FROM film WHERE (release_year = '2010');    #For some reason, all films were set to 2006 as release year?
21) SELECT title FROM film_list WHERE category = 'Horror';
22) SELECT CONCAT(first_name,' ', last_name) AS Full_Name FROM staff WHERE (staff_ID = '1');
23) SELECT title FROM film_list WHERE actors LIKE '%Fred Costner%';
24)
25) SELECT COUNT(DISTINCT country) FROM country;
    1. SELECT name FROM language ORDER BY name ASC;
26) SELECT CONCAT(first_name,' ', last_name) AS Full_Name FROM actor WHERE (last_name LIKE '%son%') ORDER BY first_name;
27) 
28) 
29) 
