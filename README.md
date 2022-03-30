# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Raul Delgado

Time spent: 3.5 hours spent in total

Link to project: https://glitch.com/edit/#!/pattern-replay?path=README.md%3A79%3A34

## Required Functionality

The following **required** functionality is complete:

* [done] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [done] "Start" button toggles between "Start" and "Stop" when clicked. 
* [done] Game buttons each light up and play a sound when clicked. 
* [done] Computer plays back sequence of clues including sound and visual cue for each button
* [done] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [done] User wins the game after guessing a complete pattern
* [done] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [done] Buttons use a pitch (frequency) other than the ones in the tutorial
* [done] More than 4 functional game buttons
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
![] https://imgur.com/aDM4hV0
![] https://imgur.com/7bnIJQT
![] https://imgur.com/SZDUarA
![] https://imgur.com/CF23Xtk

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
I did not use any outside resources besides the given instructions.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
A challenge I faced was after I had completed the game, my game would not work past the third sequence. My game would work as intended in the two sequences but when the computer would playback the third sequence, no matter what I guessed, even the correct one, I would get it wrong. After that, the game would glitch and the guess for the first sequence now became wrong even though it was right before. The way I overcame this was by going through all the code snippets that were given to me since I knew I had messed up the code somewhere therefore I started to compare it to mine. After roughly 30 minutes of scanning through, I found that my mistake was under the method playSequence(). I was initializing the same variable twice, guessCounter, which was already declared before and the one inside the method would make the counter stay stuck and that is why my guessing in the game would be wrong after failing the game once. To fix it, I just removed the initialization and left it as ‘guessCounter = 0’ instead of ‘var guessCounter = 0.’ After that, I was able to go past the third sequence and finally be able to pass the game.
3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
I have several questions, the first being if all web pages require CSS, Javascript, and HTML. I always believed that building websites only required HTML and I don't know if that is still the case. The second being is that if I were to build a site with those three, would I need to accommodate other operating systems such as Linux and Mac? The third question is if there is a limit to what Javascript, HTML, and CSS can do to a website. My fourth is how would one take live data from another source and implement it into their own website, would that be Javascript, CSS, HTML, or all three together like the site I did today.
4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had a few more hours to work on this project, I would spend them on adding additional features. My dream, after being a software developer, is to create games. While I was creating this game, it made me realize how much fun it is to change the game live to my choices and what I feel would be a good match. I would make the sequences randomized after each fail as mentioned in the prework and make an extensive interface so the user can customize their difficulty, make an endless mode that keeps on going until you can memorize the pattern anymore, add things to distract the user and make it more difficult. It would be fun to make it a multiplayer game also, a max of 4 people get to be in one lobby and it starts off everyone with four buttons and when one fails, it adds more to their own sequence and if you get it right you add to the other people's sequences. It would be a race to see who can finish first before someone else does.



## Interview Recording URL Link

https://SDSU.zoom.us/rec/share/5ONEd7mwsoEVWttlVGVPyWbAij4wnUxen1vqWqCfVMT4lXRe0Mydah-FOyxVJcxr.Qc4lp46dcqRoI-q9


## License

    Copyright Raul Delgado

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.