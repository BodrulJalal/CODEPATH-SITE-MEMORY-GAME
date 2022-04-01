# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Bodrul Jalal**

Time spent: **5** hours spent in total

Link to project: (https://lowly-flax-anglerfish.glitch.me)

## Required Functionality

The following **required** functionality is complete:

* [X] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [X] "Start" button toggles between "Start" and "Stop" when clicked. 
* [X] Game buttons each light up and play a sound when clicked. 
* [X] Computer plays back sequence of clues including sound and visual cue for each button
* [X] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [X] User wins the game after guessing a complete pattern
* [X] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [X] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [X] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x] List anything else that you can get done to improve the app!
- [X] Changed the colors of the Buttons
- [X] Included instructions to play the Game
- [X] Included Author/Creator of the Game

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

Part 1 Starting and Completing:
![](https://i.imgur.com/GFcXVM3.gif)

Part 2 Starting and Completing:
![](https://i.imgur.com/tVRvpng.gif)


Wrong Input:
![](https://i.imgur.com/rDz5AT4.gif)

Start/Stop The Game:
![](https://i.imgur.com/g1lO1mB.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

I was able to complete this project with my general understanding of computer science concepts learned from Python and C++ and the instructions given to us on the prework instructions page. I was also able to learn a few things about javascript, css and html along the way.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

Along the way, since, I have not comleted it in one sitting, I was able to understand what steps and coding I have already done since I used comments alond the way. I was able to use the comments I put to help me understand what steps were completed and what was left, as well as retrace back to what each line was used for. However, one major challenge I had was getting used to using the format of html and understanding how it worked. For example, using h1, body etc. but through quick google searches and the fact that the preview was right next to me, I was able to get a quick understanding as to the differences between each meaning.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

I would like to know how websites are able to store and extract data? The reason this intrigues me is beacuse it seems the code behind the website development is public (when you inspect element the website) but I wonder how web developers are able to pull and use private data without this being accessed by anyone.


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)
 
I would definetly add the feature of selecting a game mode difficulty. For example, I would like to implement a feature where you are able to select whether you want to go through 8 selections, 3 selections, 10 selections.. etc. This can be done through creating three seperate start buttons, each which have their own level selections that when pressed will trigger the function to start based on the level of difficulty. Then once the level button is selected, all the buttons would be hidden similar to the start button and would be replaced by one stop game button. This would be a feature that would definetely advance the game. 

Additionally, I would like to add a feature to randomize the pattern. This can be done by creating a function to create an array of numbers (1-4) of x numbers and then the program would use that array as the guide line for the correct sequence to trigger.

Finally a last feature that I would have added is a mode where the user can continue to go on indefinetely so long as they are able to select the right pattern. This would allow me to create a leaderboard feature, where the person with the highest score would be able to enter there name and have a spot on the leaderboard. 

These are just some of the simple features I would add to the concept of the game to make the game more interesting and appealing to the user. In terms of design (which I assume would be done mainy through css) I would like to keep it pretty simple in design and maybe just add some animations/transitions.



## Interview Recording URL Link

[[My 5-minute Interview Recording](https://youtu.be/nN9shegr5fo)]



## License

    Copyright [Bodrul Jalal]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.