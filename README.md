# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: \*_Brian Liao_

Time spent: **12** hours spent in total

## Required Functionality

The following **required** functionality is complete:

- [x] Game interface has a heading (h1 tab), a line of body text (p tag), and four buttons that match the demo app
- [x] "Start" button toggles between "Start" and "Stop" when clicked.
- [x] Game buttons each play a sound when clicked.
- [x] Computer plays back sequence of clues including sound and visual cue for each button
- [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [x] User wins the game after guessing a complete pattern

The following **optional** features are implemented:

- [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [x] Buttons use a pitch (frequency) other than the ones in the tutorial
- [x] More than 4 functional game buttons
- [x] Playback speeds up on each turn
- [x] Computer picks a different pattern each time the game is played
- [x] Player only loses after 3 mistakes (instead of on the first mistake)
- [x] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [x] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x] Added instructions so people will know the rules of the game
- [x] When the timer is zero the game prompts "gameover"

## Video Walkthrough

Here's a walkthrough of implemented user stories:

## Walk through of player completing the game

![](https://i.imgur.com/Yr39lXR.gif)

## Walkthrough of Case where user uses up tries

![](https://i.imgur.com/89hXzLF.gif)

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.
   - Learning about array functions in JS
   (https://stackoverflow.com/questions/351409/how-to-append-something-to-an-array)
   - Learning about generating random numbers to randomize pattern
   (https://javascript.plainenglish.io/how-to-generate-an-array-of-random-numbers-in-javascript-f883de667e84)
   - Learning about html line breaks
   (https://www.teachucomp.com/add-a-line-break-in-html-tutorial/#:~:text=To%20add%20a%20line%20break%20to%20your%20HTML%20code%2C%20you,using%20the%20tags.)
   - Learning about html lists
   (https://www.w3schools.com/html/html_lists.asp)
   - Learning about resizing my custom image
   (https://www.w3schools.com/cssref/css3_pr_background-size.asp)
   - Learning about dimensions in my css file
   (https://www.w3schools.com/css/css_dimension.asp)
   - Learning about setting a background image for css file
   (https://www.w3schools.com/cssref/pr_background-image.asp)
   - Learning about how to make a timer in JS and Html
   (https://stackoverflow.com/questions/31559469/how-to-create-a-simple-javascript-timer)

2) **What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)**
   There were a couple of things that I struggled with while doing the project. One thing was working with a language I had never worked with
   before. Prior to this prework, I had no experience in web development technologies such as JavaScript CSS, and HTML. Although logic was the
   same as previous programming languages, HTML and CSS have very different syntax and styles which is where I struggled to understand what was
   really going on with the code. Another unexpected challenge I encountered early on in this assignment is when the buttons were not playing any
   sound. I assumed there was a bug in my code and I was able to resolve it by backtracking through the prework specifications and it comparing it
   to my own code. I believe the real challenges started showing up when I started implementing the extra features for this application. The first
   4 optional features were pretty straightforward as it deals with emulating code from the walk-through and dealing with logic that is universal
   through many programming languages. But it became a lot more challenging when I was adding images to the buttons and implementing the timer. When
   implementing these two features there was one main problem In common which was connecting the interface (HTML) to the functionality (JavaScript).
   One specific scenario was when importing the pictures into my HTML file I could not get a grasp of how to connect the image element to the buttons
   in the JavaScript file for the image to popup when the button is clicked. So Instead of approaching it the way the assignment specification has
   suggested I ended up finding another solution to the problem online which required just CSS to load the button in as a photo. But adding the timer
   was not as simple because for this feature to be correctly implemented I had to have the timer show up on the interface using HTML as well as have
   it count down using Java Script. I ended up reading the suggested links that were attached to the pre-work document along with a stack overflow page
   which ended up having a code that accomplished a pretty similar task I was trying to accomplish. In the end, I ended up modifying that code while
   implementing logic and aspects that were specific for the game such as prompting gameLost() when the counter reaches 0.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)

- How does the web development differ in smaller companies as opposed to larger company? How much ownership do you get at a bigger company like google or facebook? I imagine that you get alot more freedom in smaller companies. And following up to that question what are the pros and cons of being a webdeveloper at a bigger company and at a smaller company.
- What are some of the most common frameworks in webdevelopment. Is there a specific stack that is specifically better?
- What is the hardest part about learning web development.
- What are the biggest mistakes people make when learning webdevelopment and if someone that has gone through the process is reading this, if you were to relearn webdevelopment again how would you approach it this time?
- What is the difference between software engineering and webdevelopment? It seems like the job roles overlap in many cases.
- What are the top 3 most important technical skills to have as a webdeveloper and what are the top 3 most important soft skills to have as a webdeveloper

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)
   I spent approxiamtely 3 hours on the assigned part of the project and around 9 hours researching and trying to implement the extra features.

- I would want to spend some time making the game interface look more appealing with dynamic colors and colors. For this assignment I had limited CSS and HTML knowledge so i was only able to implement flat colors which made the interface very bland and If I had more time I would like to learn more CSS and HTML features to enhance the vizual aesthetic of the page.
- I would Add levels. As each game finishes the player would be able to go onto a harder level with more rounds of patterns to guess and more buttons to guess from. Players would be able to unlock levels as they complete the previous level.
- Allowing the player to choose themes(change photos of buttons and sounds of buttons). I would want to add a feature where players could pick a theme for the game where it could change the buttons and the sound. For example there was an option for an animal theme the game would switch its buttons to certain animals and when the button is clicked it will play animal sounds. I think this would be a nice touch to add a little variety as players play the game.

## License

    Copyright [Michelel Cheng]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
