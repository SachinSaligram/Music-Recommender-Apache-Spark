
# Music Recommendation System using Apache Spark and Python

A music recommendation system to recommend new musical artists to users based on their listening history. This system employs the use of Apache Spark and the collaborative filtering technique. The Alternating Least Squares (ALS) learning algorithm is used for the underlying implementation. This project uses publicly available song data from audioscrobbler. Details can be read below.


Music Listening Dataset (Audioscrobbler.com)
--------------------------------

Data: http://www-etud.iro.umontreal.ca/~bergstrj/audioscrobbler_data.html

This data set contains profiles for around 150,000 real people. The dataset lists the artists each person listens to, and a counter indicating how many times each user played each artist.


License
-------

This data is made available under the following Creative Commons license:
http://creativecommons.org/licenses/by-nc-sa/1.0/


Files
-----

1. __user_artist_data.txt__ consisting of 3 columns
 * userid 
 * artistid 
 * playcount

2. __artist_data.txt__ consisting of 2 columns
 * artistid 
 * artist_name

3. __artist_alias.txt__ consisting of 2 columns
 * badid
 * goodid
    
_artist_alias.txt_ consists of known incorrectly spelt artists and the correct artist id.
