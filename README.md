# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Jeffrey Shen**

Time spent: **2** hours spent in total

Link to project: https://glitch.com/edit/#!/highfalutin-learned-alder
## Required Functionality

The following **required** functionality is complete:

* [ ] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [ ] "Start" button toggles between "Start" and "Stop" when clicked. 
* [ ] Game buttons each light up and play a sound when clicked. 
* [ ] Computer plays back sequence of clues including sound and visual cue for each button
* [ ] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [ ] User wins the game after guessing a complete pattern
* [ ] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
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

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](https://i.imgur.com/ZvZ2Mkh.gif)

![](https://i.imgur.com/oItAEPP.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

N/A looked at doc for references

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

I forgot to change the  `guess` function for the 4th button when I was copying and when I was testing it 
it would always tell me I lost when I pressed the 4th button and I was very confused. I ended up realizing this error
and changed it from `guess(1)` to `guess(4)`. Other than that the spec was very clear about the requirements and I think the only part otherwise 
that was a bit tough was the part with the game logic since sometimes I forgot which variable tracked what state of the game. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

I wonder how more complicated web apps are made since this seems like a lot of Javascript code just for this seemingly simple game. 
I also learned alot about how to incoporate sound and I wonder if there are some restrictions on what sounds because it could be possible that 
web apps plays very obnoxious sounds just from opening the application and wonder how to prevent that. I also wonder how the hiding the button works with adding
and removing and wonder if there are other ways to do it as well. 


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

Add a current score to the game so that the user can see what their current score it and what the highest score they've gotten is. I would also try to make the code for the button more modular and reduce 
the number of copy paste needed in this assignment. We could also try to incorporate other languages like React to add components that ensure our code isn't as reliant on copy pasting. 



## License

    Copyright Jeffrey Shen

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.