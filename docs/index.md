## Summary

The software I want to develop is a puzzle game where you have to navigate through a dungeon like 
maze. In the game you will spawn at the start of the dungeon and be given a move limit, if you don't
get to the end in that move limit you die and have to start all over, the dungeon doesn't change, so
use anything you learned in the previous run to help you in the next run. the game is played from a
top down perspective where moving to a new tile shows a few tiles in front of you. When you reach 
the end of teh dungeon you move onto the next level.

## Intended users

* People who enjoy difficult puzzle games

    > As someone who enjoys a decent challenge I love puzzle games, I want a difficult puzzle game I
  > can play anywhere, so that I'm never bored with easy games or having to carry one of those mind 
  > game puzzles on me.

* People who like mobile games

    > As someone who plays a lot of mobile games because I don't have a computer or console, I want
  > a well-designed mobile game that will keep me entertained and doesn't have ads every minute.

## Client component

* **Functionality**

  * A button that says start run
  
  * An indicator of what level you're on
  
  * A button that will show you teh solution if you get stuck on a level
  
  * A Dpad so that the player can move around the maze

* **Persistent data**

  * What level the user is on
  
  * Where the user is in a stage if the user quit midway through a run
  
  * the solutions to the stage in case the user wants to learn the stage while not connected to wifi
  
  * How many tries the level took, and if you used the hints/solutions
    
* **Device/external services**

  * Google sign in
  
  * Leaderboard rankings
    
## Server component

* **Functionality**

  * The stage the user is currently on 
  
  * A leaderboard so you can see what level your friends have gotten to 
  
  * The amount of tries a level took other people to complete
=
* **Persistent data**

  * What stage the user was on the last time they played with an internet connection
  
  * A leaderboard function so people can see how many levels they've done compared to other people
    
* **External services**

  * Google sign in
    
## Stretch goals/possible enhancements 

  * an endless mode that generates off of a few basic templates that get longer and longer the 
    farther you got, in the beginning it would be 3 or 4 of the templates put together with adjusted
    move counts, and farther in it uses 9 or more templates in the same level (not saying there is 9
    templates)