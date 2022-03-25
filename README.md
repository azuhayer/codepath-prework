# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Zuhayer Alvi

Time spent: 9 hours spent in total

Link to project: https://glitch.com/edit/#!/childish-zippy-silver

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](http://g.recordit.co/n3u0R23JxP.gif)
![](http://g.recordit.co/nFDOMXJ5n9.gif)
![](http://g.recordit.co/SsTe8CNyNu.gif)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

Stackoverflow.com 

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

My greatest challenge while working on this submission was adding code to the "guess" function in the script.js file. This was indeed a challenge because I had to figure out the technicalities of the game logic and how I should go by implementing it in JavaScript code. In order to conquer this challenge I first looked at it from a flowchart perspective. I knew that in order to win the game a players had to correctly click on each of the buttons that were shown. So, every time that a guess was correct and the turn was not over, I had to increment the "guessCounter" function. And once the turn was over but the player did not choose the right button, I had to increment the "progress" function. If it was the last turn and the player did in fact choose the right button, they would win the game. I also knew that this function would be a bunch of "if" and "else" statements as well. I checked websites to refresh my memory on if statements and then started to implement my code according to the fucntions for the game logic. And thus, I was able to implement the code for the "guess" function by looking at the problem step by step.       

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

Some questions about web development that I have: What is the purpose of web development technologies such as Node.js or even React.js? Are they mainly used to make websites more dynamic? Are web development engineers considered Frontend or Full Stack? Is using GitHub indicitive of what actual web development engineers do on their day to day work routine?    

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had a few more hours for this project, I would certaintly consider adding more buttons and speeding up the time that a sound is played from a button to make the game a whole lot more challenging for the player. I would also try to put a difficulty selector that allows players to choose what difficulty that they would like to play in so that they could try out the game at an easier difficulty and go up to higher difficulty to challenge themselves. 



## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.loom.com/share/c8a6d6ba0ee74c5d9fb9ccc238bdbe66)


## License

    Copyright Zuhayer Alvi 

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
