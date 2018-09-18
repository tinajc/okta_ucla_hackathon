# okta_ucla_hackathon
We started off with pre-existing alexa skill repository, the trivia quiz. We implemented their functions to make a guess the name of the song where a player gets two seconds of the song/music and has to guess the name of the song.

Front-end was our alexa voice user interface using JSON. We added a statsIntent so that we can keep track of the player's score. With this, we were hoping to capture what player's preference of music genre.

Back-end or the Lambda function was implemented using Node.js. Newquestion.js was written to better fetch the data when needed, and stores the question database. We implemented Okta API in index.js to create and save user profiles. Postman is used to store user database.

To play the game, a player account is automatically created. The player has a Hip Pop score, a Pop score and a Jazz score that keep track of number of songs the player guessed correctly for each genre. 
This information could potentially be used for music applications to recommend songs according to player's familiarity with each genre. The game prototype could be improved to incorporate multiple user accounts and to allow players compete by adding a leaderboard that ranks players by their total scores.
