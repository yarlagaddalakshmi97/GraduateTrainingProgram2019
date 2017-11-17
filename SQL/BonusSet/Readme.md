# Bonus Problem-set

In this Problem-set you are tasked to write 12 SQL queries on a relational movie database. 

You will first need to import the movie database in your database system. 
You can obtain the data from [here](https://courses.cs.washington.edu/courses/cse444/06wi/hw/IMDB.zip)

The database consists of seven tables, however you will be using only the following five tables
ACTOR (id, fname, lname, gender)
MOVIE (id, name, year, rank)
DIRECTOR (id, fname, lname)
CAST (pid, mid, role)
MOVIE_DIRECTOR (did, mid)

Notes:
--------
id column in ACTOR, MOVIE & DIRECTOR tables is a key for the respective table.  
CAST.pid refers to ACTOR.id, CAST.mid refers to MOVIE.id
MOVIE_DIRECTOR.did refers to DIRECTOR.id and MOVIE_DIRECTOR.mid refers to MOVIE.id 

1. List all the actors who acted in at least one film in 2nd half of the 19th century and in at least one film in the 1st half of the 20th century
1. List all the directors who directed a film in a leap year 
1. List all the movies that have the same year as the movie 'Shrek (2001)', but a better rank. (Note: bigger value of rank implies a better rank)
1. List first name and last name of all the actors who played in the movie 'Officer 444 (1926)'
1. List all directors in descending order of the number of films they directed
1. Find the film(s) with the largest cast.   
1. Find the film(s) with the smallest cast.
1. In both the above cases, also return the size of the cast.
1. Find all the actors who acted in films by at least 10 distinct directors (i.e. actors who worked with at least 10 distinct directors).
1. Find all actors who acted only in films before 1960. 
1. Find the films with more women actors than men.
1. For every pair of male and female actors that appear together in some film, find the total number of films in which they appear together. Sort the answers in decreasing order of the total number of films.
1. For every actor, list the films he/she appeared in their debut year. Sort the results by last name of the actor.
1. The Bacon number of an actor is the length of the shortest path between the actor and Kevin Bacon in the "co-acting" graph. That is, Kevin Bacon has Bacon number 0; all actors who acted in the same film as KB have Bacon number 1; all actors who acted in the same film as some actor with Bacon number 1 have Bacon number 2, etc. Return all actors whose Bacon number is 2. 
1. Suppose you write a single SELECT-FROM-WHERE SQL query that returns all actors who have finite Bacon numbers. How big is the query?
1. A decade is a sequence of 10 consecutive years. For example 1965, 1966, ..., 1974 is a decade, and so is 1967, 1968, ..., 1976. Find the decade with the largest number of films.
1. Rank the actors based on their popularity, and compute a list of all actors in descending order of their popularity ranks.  You need to come up with your own metric for computing the popularity ranking.  
   This may include information such as the number of movies that an actor has acted in; the 'popularity' of these movies' directors (where the directors' popularity is the number of movies they have directed), etc.  
   Be creative in how you choose your criteria of computing the actors' popularity.   For this answer, in addition to the query, also turn in the criteria you used to rank the actors.