# 08-liri-node-app
  The liri bot has the ability to conduct searches of Spotify Songs, Concerts and Movies and provide accuartate specific pieces of information about each. 
  
## Accessing Node
    Before you can run any commands or install any JSON packages, you need to intialize Node and make sure that it is running in your terminal in the right local folder. 
  ![node](https://raw.githubusercontent.com/AaronMKelley/08-liri-node-app/master/Accessing%20Node.png)
  ![node](https://raw.githubusercontent.com/AaronMKelley/08-liri-node-app/master/Accessing%20Node(2).png)
## Spotify This Song
    The first function of the liri bot is the ability to take the title of a song and be  provided with: 
       1. The song's name
       2. A preview link of the song from Spotify
       3. The album that the song is from
        To access this search, in the terminal one will input "node liri.js spotify-this-song <<insert song title here>>". If no song title is inputed then the search will default to "The Sign" by Ace the Base (results actually show "sign of the times" by Harry Styles. 
  ![node](https://raw.githubusercontent.com/AaronMKelley/08-liri-node-app/master/Spotify-This_song.png)
  ![node](https://raw.githubusercontent.com/AaronMKelley/08-liri-node-app/master/Spotify-This-No-Song.png)
  ## Concert This 
    This second function of the liri bot is the ability to input thr name of a music artist and be provided with: 
       1. Name of venue(s)
       2. Venue location(s)
       3. Date of the Event (in MM/DD/YYYY form)
    To access this search, in the terminal one will input "node liri.js concert-this <<insert name of artist here>>".
  ![node](https://raw.githubusercontent.com/AaronMKelley/08-liri-node-app/master/Concert-This.png)
  ## Movie This 
    Third function that the liri bot can conduct is the ability to input the title of a movie and provide the user with:
        1. Title of the movie.
        2. Year the movie came out.
        3. IMDB Rating of the movie.        
        4. Rotten Tomatoes Rating of the movie.
        5. Country where the movie was produced.
        6. Language of the movie.
        7. Plot of the movie.
        8. Actors in the movie.
    To access this search, in the terminal one will input "node liri.js moive-this <<insert title of moive here>>". If not title is inputed then the search will default to the movie "Mr Nobody"  
   ![node](https://raw.githubusercontent.com/AaronMKelley/08-liri-node-app/master/Movie-This.png)
   ![node](https://github.com/AaronMKelley/08-liri-node-app/blob/master/Movie-This-No-Title.png)
        
