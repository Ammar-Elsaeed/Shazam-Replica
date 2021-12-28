# Shazam-Replica
In this task, we create a desktop application that lets the user provide a song, and the application returns its closest matches from songs in the database. 
the user can also use the GUI to select two songs, mix them, and search for the closest match of the resulting mix. 

# Key points
## 1. Create a database for the songs
to create a database for our application we did the following:
  1. downloaded different songs, split them to vocals and music files.
  2. loaded the three files for each song and calculated the spectrogram features for them
  3. generated hashing for the features and saved it in a json file. 

## 2. Create a simple GUI 
the GUI lets the user choose a song, then the program automatically generates its hashed spectrogram features and compares it to the ones stored in the database. a list of the top 
matches found is displayed on the GUI, along with a similarity index to indicate how close the song is similar to the matches in the list. 


