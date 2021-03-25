# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Brandon Cao**

Time spent: **5** hours spent in total

Link to project: (insert your link here, should start with https://glitch.com...)
https://glitch.com/edit/#!/ballistic-clear-sardine?path=README.md%3A10%3A0

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
![](your-link-here)
https://cdn.glitch.com/c2c25c42-8c23-4fff-bf4c-7ce4e2e5e548%2FlightAndSoundGame.gif?v=1616634383544

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
I did not use any outside sources to assist me with this project.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
The main challenge I found was the sound not working at all. After checking back and forth with what the tutorial had and the code that I had,
I thought something seemed off and I was able to spot an error in the tutorial code that featured a comma rather than a period in the playTone function.
After making the changes, the sound started to function.
What was still difficult though is the sounds the clue makes where it doesn't stop making the sound of the last played button.
I wasn't sure why it wasn't working, because all the variables seemed to be in place and in the right order. The hold time is 1000 milliseconds, which is one of the variables playSingleClue was passing to playTone.
playTone took len as a parameter, which was hold time, where it would then play the stopTone function after said time has elasped, but it never did. I couldn't find out why.
Other minor challenges I faced was installing and using the recording software since I never used any kind of software before.
After some experimenting, I was able to utilize the recording software, made a recording of what I have, and after some time, found out how to turn the gif into a link.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
Not really much questions. It all seems very similar in terms of what I went over in my programming classes. Only questions I would really have is more about
the .css file features (such as using more types of fonts, colors, sizes, and if there is any other formatting tool that wasn't mentioned),
the .html features (such as making more headers of different sizes, more buttons that have different functions, and other tools like a search bar maybe),
and how to improve the sound effects, most importantly learn how to terminate a sound effect after it plays for a set amount of time.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had more time on this prokect, I would first try and fix the bug where the sound from the last played clue would play indefinitely. After that, if I still had additional time, my first course of action
would be adding a strike system to the game, allowing players multiple chances instead of getting an outright game over for a potential mistake they made.



## License

    Copyright Brandon Cao

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.