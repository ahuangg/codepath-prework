# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's FutureForce Tech LuanchPad Program.

Submitted by: **Alan Huang**

Project Live Link : (https://juvenile-polar-tumble.glitch.me/)

Link to project: (https://glitch.com/edit/#!/juvenile-polar-tumble) 

## Required Functionality

The following **required** functionality is complete:

- [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [x] "Start" button toggles between "Start" and "Stop" when clicked. (Start Leads to Menu instead)
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
- [x] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [x] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x] Cat Theme
- [x] Organized Code 
- [x] Home Page with Demo Video 
- [x] Link to Github repo Onpage 
- [x] Counter for Mistakes, Progress, and Timer 
- [x] Previous Score & Total Wins
- [x] Menu with 3 different Difficulty Modes (Easy, Medium, Hard) 
- [x] Speed Mode (One Life, 1 Round with 6 Patterns) 
- [x] Legacy Mode (Original Game Mode) 
- [x] Custom Mode ( User gets to choose Score, Pattern size, Mistakes, Timer and Speed) 
- [x] Custom Sounds for Winning and Losing 

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

    Landing Page, Demo Video (Please Pause Video Before Clicking Start),
    Game Menu with 3 Difficulties, Speed Mode & Custom Mode.

![](https://i.imgur.com/hBR2MXA.gif)

    Legacy Mode (Original Game Design from Demo), Homage to the Original Game Design

![](https://i.imgur.com/PMKejW4.gif)

    Easy Mode, Game Layour for 4 Buttons, Counter Bar (Progress, Mistakes Used, Time Left)
    & Decrease in clueHoldTime Speed per round.

![](https://i.imgur.com/g6OAQe0.gif)

    Medium Mode, Game Layout for 6 Buttons & Stop Button (Loses & Ends Game).

![](https://i.imgur.com/ZmT6mgu.gif)

    Hard Mode, Game Layout for 8 Buttons & Reset Button(Resets Game).

![](https://i.imgur.com/iDLA5Ro.gif)

    Speed Mode!!! 1 Round, 1 Mistake, Fast ClueHold Times & only 8 seconds to see,
    hear and playback pattern.

![](https://i.imgur.com/BrUqjl2.gif)

    Custom Mode :D Choose your own Progress, Pattern Size, Mistakes, Speed & Time from provided options.

![](https://i.imgur.com/rWiBNqu.gif)

    Previous Score Button (Only Shows Previous Score, {Points Scored, Mistakes Used, Time Left})

![](https://i.imgur.com/fgyN1Ke.gif)

    Losing by Mistakes (Easy: On 4th Mistake, Medium: On 3rd Mistake,
    Hard: On 2nd Mistake, Speed: On First Mistake)

![](https://user-images.githubusercontent.com/98438095/164167582-af8b0e22-084d-45e6-ab6c-cd5edbe640f2.gif)

    Losing by Running out of Time, Winning & Increase in Total Win Counter (Top Right).

![](https://i.imgur.com/H8EV1DH.gif)

    Winning Text & Clickable icon with access to Github Repository (Bottom Left).

![](https://i.imgur.com/eHM36F1.gif)

GIFs created with [LiceCap](https://www.cockos.com/licecap/)

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.

   &emsp; :notebook: HTML/CSS/JS tool: [StackOverflow](https://stackoverflow.com/),
   [MDN](https://developer.mozilla.org/en-US/), [FreeCodeCamp](https://www.freecodecamp.org/)

   &emsp; :hammer_and_wrench: Tools: [HackMD](https://hackmd.io/), [Glitch](https://glitch.com/), [GitHub](https://github.com)

   &emsp; :camera: IMG's & Sound: [Adobe Creative Cloud](https://express.adobe.com/tools/), [Google Images](https://images.google.com/), [MixKit](https://mixkit.co/)

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)

   &emsp;A challenge I faced during this submission was cleanly separating the logic between the different parts of my web application. I am using HTML and CSS to structure and style the user interface while using JavaScript to drive the core functionality. While writing JavaScript, I had to take extra precautions to ensure my code was written cleanly. To overcome this challenge the solution I came up with was to modify the DOM by utilizing classes. I assigned a combination of classes to the various elements I wanted to display and hide. I used iteration in order to switch the display property for each of the elements. This was beneficial to me since it cut out a lot of boilerplate and reduced redundancy in my code. Another challenge I faced was with the count-down timer. In the beginning, it was not functioning properly as it was counting down too quickly and going below zero. By researching this problem, I came across the official documentation for time functions in javascript. Reading through this helped me better understand how to rewrite the timer function to have its functionality align with the specifications. As my skills with these tools increased, so did my confidence. The features I wanted to implement suddenly became possible, and what I envisioned for this project started coming together. Looking back, the main reason I was able to overcome the challenges I faced was because of my perseverance. It stopped me from giving up and allowed me to work through many roadblocks. Going forward, I am more confident in my abilities in creating and launching projects related to web development. I am proud of what I was able to accomplish with this web project and look forward to creating more.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)

   &emsp;I learned a lot about web development through this project. Completing this submission made me more intrigued about Web Development. Which brought about more questions. Since I first learned about Salesforce a few years ago, I’ve been interested in how it works. I read a statistic that 95% of the companies in the Fortune 100 run at least one app from the Salesforce AppExchange. I am eager to learn how technologies such as AWS, Heroku, React, Postgres, SQL, and MongoDB are used at Salesforce to allow scaling to 150,000+ users. Learning technology has always been a passion of mine, and I’d love to see and learn about the technologies powering the largest CRM in the world. I want Salesforce to be part of my journey as I continue to expand my knowledge and answer these questions, whilst growing my ability as a web developer.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)

   &emsp;If I had a few more hours to work on this project I would most definitely make the user experience more enjoyable by making the website more interactive. To do this I would redesign the layout of the website and implement more features. One aspect I want to implement is having written rules alongside the demo video so the user does not always have to click on the video to learn the game. I’m also looking to refactor the menu in which I would implement a dropdown menu selection. This dropdown menu would overlap with the current page the user is on, and this would allow the user to pause a game if they are currently in progress. The menu will also be redesigned with a new UI to better match the theme I was going for and make my game look more aesthetically pleasing. My last idea is to improve the tracking feature. Instead of just displaying the total amount of wins and the previous score, I would like to build upon this and build a full-on scoreboard that would track the top 10 scores across the different game modes. This feature would also let the user see their total win-loss ratio across the different games. These changes will slightly alter the way the game is played while still maintaining the original layout of the Light and Sound Memory Game. Although some of these features seem minor, it adds dimension and pushes the game to be more interactive. In my opinion, attention to detail is very important, since it can make or break the overall user experience.

## Interview Recording URL Link

[:movie_camera: My 5-Minute Interview Recording](https://www.loom.com/share/edcfff2ee7814fb68fbbec9c0b5a1204)

## Thank you for taking your time to review my work and have a great rest of your day!

## License

    Copyright [Alan Huang]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
