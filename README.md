# businessOutFittedBob-game
Game made app by bundling together JavaScript code needed and phaser.js
Already made comments in the code files describing how it works!

The game starts with the startScene, then moving on with gameScene to play the game using the (up, down, right, left) arrow keys.

Start by collecting the money using bob, and every collect increases the score starting from 100 to a randomized number increase up to above a 1000

Avoid the files during the game, they are put randomized!!

This is the code to check collision between Bob and edges of the canvas of the game
if(bobXCoord <= 32 || bobXCoord >= 448){
      this.endGame();}
similarly to thy Y Coord.

The game restarts with 0 score if endGame.

Try out the Game using the URL Below:

radiant-nougat-c5312b.netlify.app
