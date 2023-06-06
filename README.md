# Pop_the_lock_game
Code for the game "Pop the Lock" running the adafruit circuit playground express.
Auther: Sean Carver

## Object of the game
The object of the game is to time your button presses to pop the lock for each level.
Once you pass all ten levels, you win! Be warned, the speed of the moving led will progressivly get faster with each level. 
For bragging rights and high score, be quick and press the button before the led moves past the lock led for two points. 
Be fast as every time the led passes the lock led, the scoring for the level will go down by one. 

## How to play
(written for the Circut Playground Express, orinated with the cord pointing down)

When you boot up the game it will be in an idle mode light show. 
Press the left button to start the game
Both left and right buttons will work to pop the lock.
For a harder mode, move the onboard switch to either side while in idle mode, you will here two beeps. The game will now be faster. 

Time your presses correctly for when the moving led is in the same location as the lock led. 
If your press is right, you will move to the next level, if not, the game is over.
If the level was failed, you will hear your score and see where the moving led was when you pressed.

The game will reset after either you win, or lose. and is ready to play again. 
If in hard mode, after the game is complete, it will reset to normal mode.

Scoring: 
Press the button before the moving led passes the lock led for two points
Press the button after one pass, score 1 point
Pressing after two or more passes, score 0 points. 
Points from each level will add to your current score. 


## What the code is doing 
