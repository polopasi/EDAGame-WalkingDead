# EDAGame-WalkingDead

The Game of EDA in UPC FIB.
In the folder, there is the rules, guide and example files (along with some of my versions).

Rules and guide are written in "regles-TWD-1.pdf". 
Inside the folder "game" there's all the necessary files to execute the game, along the folder "Viewer", which lets you see the result of a game.

How to run:

-To add a player; for example, Rick, copy the file AINull.cc (empty player) and change the next line :
  #define PLAYER NAME Null      to    #define PLAYER NAME Rick


-Start creating your player implementing the function play()!


-To compile the game and all the players:

    make all
  

-Create (or replace) a file default.res with the content of a game. Player1...Player4 are the NAMES of the players, -s seed is the random seed:

    ./Game Player1 Player2 Player3 Player4 -s 30 < default.cnf > default.res
    
    
-Once generated, open the Viewer, clicking viewer.html from the folder "Viewer" and loading the default.res file. You will see the game, round per round.


There's a list of functions you can use in api.pdf.

IT'S LIKELY I forgot to explain something important, but there's everything written in the "regles-TWD-1.pdf".

Have fun!

  
  
    
  
  
