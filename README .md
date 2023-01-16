
# Song Reconmender

Created as part of the Ironhack Data Analysis Bootcamp.
This program takes a user given song title and artist and reconmends
a similar song either from the popvortex Top100 list, or according do spotify audio features.



## Authors

- https://github.com/GiancarloSanna


## Files



- Data Folder
- csv files of the collected songs
- csv files of the classified songs


- Main Folder
- 01 Data Collection: In this notebook, the song files get collected from spotify
- 02 Clustering: Classifying the collected songs
- 03 Reconmender: Using the classified songs to build a song reconmender. It acceppts classification models and classified data of different granularity.

- kmeans10.p - kmeans45.p : Pickled classification models
- pca.p, scaler.p : Principal component analysis parameters and scaling parameters for usage on newly enetered songs in notebook 3