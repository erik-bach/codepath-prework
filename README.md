# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: Erik Bach

Time spent: 3 hours spent in total

Link to project: https://glitch.com/edit/#!/mini-available-weaver

## Required Functionality

The following **required** functionality is complete:

- [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [x] "Start" button toggles between "Start" and "Stop" when clicked.
- [x] Game buttons each light up and play a sound when clicked.
- [x] Computer plays back sequence of clues including sound and visual cue for each button
- [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [x] User wins the game after guessing a complete pattern
- [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

- [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [x] Buttons use a pitch (frequency) other than the ones in the tutorial
- [x] More than 4 functional game buttons
- [x] Playback speeds up on each turn
- [x] Computer picks a different pattern each time the game is played
- [x] Player only loses after 3 mistakes (instead of on the first mistake)
- [ ] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](gif1-link-here)
![](gif2-link-here)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.

  I used stackoverflow for help on generating an array with random numbers and I used mozilla's documentation of the Math.random() and Array.from() function.
  
  https://stackoverflow.com/questions/5836833/create-an-array-with-random-values
  
  https://developer.mozilla.org/en-US/docs/web/javascript/reference/global_objects/math/random
  
  https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/from
  

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)

  One of the challenges I encountered while creating this submission was generating an array with random numbers in it. I am not so familiar with javascript, so I was not aware of the syntax or functions that could help me generate some random numbers. My first approach was to create a function that will clear the pattern array and generate new random values for the array. However, I was quite stuck on the functions that I should be using to help me do so. I then referred to Mozilla's documentation on the Math.random function to gain more insight into how the function works. Once I gained an idea of how it works, I experimented with the function to try to create an array of length 8 with random values from 1 to 6. I was running into some errors with assigning the output of my function to the pattern global variable, so I first isolated my function in a different environment to see if I was getting the correct output. I then looked through the logic of the startGame() function to see where it would make sense. My issue was that I was creating the random pattern array after calling the playClueSequence() function, when I should have been placing the randomPattern() function at the start of the startGame() function. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)

  I am curious to learn more about front-end and full-stack development. This was my first time with any front-end technologies, but it was very fascinating to learn about. I am interested in learning more about the potential of front-end technologies and how the development cycle differs from back-end to front-end. I am also curious to learn more about how we can integrate languages like java, c++, and python into the web development cycle. I would also like to know how we can collect data from user interactions with our websites and how a team would utilize that information to create a better product.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)
   
  If I had a few more hours to work on this project, there are a few features and improvements that I would want to make. The first improvement I would make is changing the logic of the guess() function. Based on my experience with previous languages, there is probably a cleaner way to write the logic of that function. Also, I would add some features like a high score counter and a difficulty option. The difficulty option would change the length of the pattern and the speed at which the pattern is displayed. I would also code in a variation where only the sound is played and you have to match based on that. I would also want to implement an endless mode. I'm also interested to see if there is any possibility of adding multiplayer functionality to the game.


## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)

## License

    Copyright [YOUR NAME]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
