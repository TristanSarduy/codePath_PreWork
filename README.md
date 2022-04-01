 Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Tristan Sarduy**

Time spent: **3.5** hours spent in total

Link to project: (https://lightandsoundgameprework.glitch.me/)

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [ x] Computer plays back sequence of clues including sound and visual cue for each button
* [ x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [ x] User wins the game after guessing a complete pattern
* [ x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ x] More than 4 functional game buttons
* [ x] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](http://g.recordit.co/O0UcvpTThh.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
I used w3schools

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
There were a couple challenges I encountered while creating this project. However, the most significant one was the end where 
I had to code my own guess function. What I struggled with was my approach to this function. At first, I decided to use
a for loop that would loop as long as the game was active. It would loop the functions until either someone beat the game
or lost. The problem was that the for loop did not account for the time it would take the player to click the buttons. 
In other words, it would not stop to check for the players repsonse and would instead loop until the condition statement was 
reached, this would cause the entire system to not work as it would not allow the player the chance to follow the pattern 
and would always end up with the players pressing the wrong button.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
My question about web development is how does one save data from their website to a central database? In this project we
checked the users responses and compared it to the information stored in an array, but what if we wanted to save these user
responses so that it could be accessed at any time from any device? 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had more time to work on this project, then I would spend most of my time focusing on two things. First, I would like to create pause and repeat buttons.
These buttons would allow the player to pause in the middle of the pattern being shown as well as being able to see the pattern once again
if they were not able to follow it the first time. Second, I would like to add different 'levels'. I would make it so the player would first
have to answer a system prompt asking the player to choose one of the different available levels, each with a different pattern, and possibly 
different sounds, colors, and designs to each button to make each level more unique.



## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright [Tristan Sarduy]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
