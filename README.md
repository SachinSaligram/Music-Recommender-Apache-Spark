
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

user_artist_data.txt
    3 columns: userid artistid playcount

artist_data.txt
    2 columns: artistid artist_name

artist_alias.txt
    2 columns: badid, goodid
    
'artist_alias.txt' consists of known incorrectly spelt artists and the correct artist id.
