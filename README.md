# Flappy Bird
For this Android Studio Project, we have to recreate a *Flappy Bird game*.
![image](https://github.com/SebasTol-777/Galaxy-Luppyx/assets/127360986/75769ad5-f63a-4a64-a795-8258c8c3a08b)


## What is it ?
In this game, the player is a bird which has to avoid pipes by flapping (when we click on the screen, the bird goes up and down after). For each pipe we avoid, we have 1 point. We lose the game when our bird touches a pipe. Once we lose, our score is registered on a database with our pseudo and we can see the leaderboard.


# 15/10/2021
## API
We created a simple API which has 2 roles: 
* Get (name and score of the player) data from the app and insert it or update the existing player in database
* Fetch all the players from database, order them by score and return a JSON file

We are able to get the name and a fake score of the player a  Top10 leaderboard from all the players who are in our database. The next step is creating the acutal game.


## Thank you ! :)
