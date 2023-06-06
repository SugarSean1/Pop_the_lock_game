# Pop_the_lock_game
Code for the game "Pop the Lock" running the adafruit circuit playground express.
Auther: Sean Carver

## Object of the game
The object of the game is to time your button presses to pop the lock for each level.<br />
Once you pass all ten levels, you win!<br />
Be warned, the moving led will change direction and get faster with each level, and the lock led with randomly change position.<br />
For bragging rights and high score, be quick and press the button before the led moves past the lock led for two points.<br />
Be fast as every time the led passes the lock led, the scoring for the level will go down by one.<br />

## How to play
(written for the Circut Playground Express, orinated with the cord pointing down)

When you boot up the game it will be in an idle mode light show. <br />
Press the left button to start the game. <br />
Both left and right buttons will work to pop the lock. <br />
For a harder mode, move the onboard switch to either side while in idle mode, you will here two beeps. The game will now be faster. <br />
<br />
Time your presses correctly for when the moving led is in the same location as the lock led. <br />
If your press is right, you will move to the next level, if not, the game is over. <br />
If the level was failed, you will hear your score and see where the moving led was when you pressed. <br />
<br />
The game will reset after either you win, or lose. and is ready to play again. <br />
If in hard mode, after the game is complete, it will reset to normal mode. <br />
<br />
### Scoring:

Press the button before the moving led passes the lock led for two points <br />
Press the button after one pass, score 1 point. <br />
Pressing after two or more passes, score 0 points. <br />
Points from each level will add to your current score. <br />
The higest score posible is 20. <br />

## About this project, acknologment, and sources.

This game was created to mimic the arcade game Pop the Lock, and as a final for an ENGR class and future use in fully developed handheld game.
The inputs for this game is the left, right and switch on the Circut Playground Express. <br />

The outputs and sources: <br />
rainbow pattern idle mode, adapted from: https://learn.adafruit.com/circuit-playground-kaleidoscope/inside and Chet Udell. <br />
Songs generated with "midi note claculations" Source: Chet Udell, 2023 https://github.com/udellc <br />
Speech sound effects: Aurdino examples, Talk_US_Male library <br />
Sparkle win pattern & Starting red, yellow, go pattern: Sean Carver <br />
Midi tones: Sean Carver <br />
<br />
Final concept and creation was by Sean Carver <br />
