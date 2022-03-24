 # Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Valerie Michel**

Time spent: **6** hours spent in total

Link to project: (https://glitch.com/edit/#!/kaput-climbing-stage)

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
* [x] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [x] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![x](https://i.imgur.com/BC6lNtN.gif)
![x](https://i.imgur.com/HJVN72N.gif)
![x](https://i.imgur.com/Jg9QAxG.gif)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[https://stackoverflow.com/questions/14474452/can-i-change-the-color-of-font-awesomes-icon-color
https://www.youtube.com/watch?v=t2kpDpAl7y8
https://codeburst.io/javascript-increment-and-decrement-8c223858d5ed
https://www.freecodecamp.org/news/var-let-and-const-whats-the-difference/]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[The biggest challenge I encountered was trying to have the playback speed up on each turn. I first tried toying with it myself to see where I can decrement the time on already existing elements, but either the entire game stopped functioning, or my entire screen would freeze. After taking a look at one of the errors the console gave me, I realized that I was trying to change a 'constant variable'. When I looked it up, I discovered that I need to change the variable declarations from 'const' to 'let' to allow the values to be updated later on. I still couldn't get the game to speed up using the elements that were already there, so I decided to create a new function specifically meant for decreasing the inital values and declaring it in the guess function (where he logic of the game is located). After testing it in the browser, it finally worked.]


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[Since javascript is the language I have less experience with, I would like to know how much logic goes into creating functions. I'm often unsure of how many steps need to be taken to get a function to operate properly as well as how many variables should be declared. I'm also curious about changes in web devel;opment as web design trends change and evolve. My first few interactions with Javascript years ago didn't include declarations like let or const, so I would like to know in what ways they've helped improve building websites and apps.]


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)
[If I spent a few more hours on this project, I would like to have it so that the alert/pop-up wouldn't come from the browser. In other words, I would like to create a special stylized pop up for when someone either wins or loses the game. I would also change each button to a different sound effect rather than a tone. For example, I would use a water droplet sound, a twinkle, a bell and 8-bit sounds (for the game controller).]



## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.loom.com/share/0646ef77d65e4f47b02dbf4a35c8c8ee?sharedAppSource=personal_library)


## License

    Copyright [Valerie Michel]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
