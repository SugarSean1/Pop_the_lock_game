# Pop_the_lock_game
Code for the game "Pop the Lock" running on the adafruit Circuit playground express.
Author: Sean Carver

## Object of the game
The object of the game is to time your button presses to pop the lock for each level.<br />
Once you pass all ten levels, you win!<br />
Be warned, the moving led will change direction and get faster with each level, and the lock led will randomly change position.<br />
For bragging rights and high score, be quick and press the button before the led moves past the lock led for two points.<br />
Watch out, everytime the led passes the lock led, the scoring for the level will go down by one.<br />

## How to play
(written for the Circuit Playground Express, oriented with the cord pointing down)

When you boot up the game it will be in an idle mode light show. <br />
Press the left button to start the game. <br />
Both left and right buttons will work to pop the lock. <br />
For a harder mode, move the onboard switch to either side while in idle mode, you will hear two beeps. The game will now be faster. <br />
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
The highest score possible is 20. <br />

## About this project, acknowledgement, and sources.

This game was created to mimic the arcade game Pop the Lock, and as a final for an ENGR class. Future use and refinement for handheld game.
The inputs for this game are left, right and switch on the Circut Playground Express. <br />

The outputs and sources: <br />
rainbow pattern idle mode, adapted from: https://learn.adafruit.com/circuit-playground-kaleidoscope/inside and Chet Udell. <br />
Songs generated with "midi note calculations" Source: Chet Udell, 2023 https://github.com/udellc <br />
Speech sound effects: Ardino examples, Talk_US_Male library <br />
"Sparkle win" pattern & "Starting red, yellow, go" pattern: Sean Carver <br />
Midi tones: Sean Carver <br />
<br />
Final concept and creation was by Sean Carver <br />
