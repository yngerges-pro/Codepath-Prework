# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Youstina Gerges**

Time spent: **5** hours spent in total

Link to project: (https://delicious-snowy-argument.glitch.me/)

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
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](http://g.recordit.co/aenkE18Rw1.gif) 
![](http://g.recordit.co/RJOUq4n6ke.gif)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
	
	I only used the prework site, nothing else.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
	
	I had some difficulty with gradually speeding up the game. So far, I managed to speed up the whole game at a constant speed by playing around with JavaScript. I did that by getting rid of “delay += clueHoldTime;” and adding a “for loop”. I assumed that the for loop would help me gradually make the game gradually speed up. However, the system was ignoring the “for loop” for some reason. The good news was that I had an idea of how to speed up the game. The bad news was that I couldn’t do that on my own. I then realized that I was overcomplicating everything. I looked back at my prework site for clues. It stated that “Think carefully about how much time to shave off!” I then remembered how the “var clueHoldTime” has a number of 1000. I then realized that I am supposed to subtract a number from the 1000 each time to gradually speed up the game. I put back the “delay += clueHoldTime” since there needs to be a delay in between sounds. Then I added, clueHoldTime -= 45. It took me a while to adjust the speed and the number of the pattern of the lights so the clueHoldTime’s number wouldn’t reach 0 or maybe even a negative number. The fact that I was able to figure this out without any knowledge of JavaScript and little coding experience makes me feel like I did something on my own.  

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
	
	I was wondering if I could learn more about JavaScript. What is the difference between Java and JavaScript? What commands does JavaScript have that are similar to Java? So far, I realized that Java and JavaScript both have an if, loop, and +=  & -=  commands.  I also wonder how GitHub works. How do you use GitHub? What is GitHub used for? What resources does GitHub have? Does every web developer use GitHub? Would I use GitHub in my career? What type of problem solving does it do in the “real world”? Are we going to be mostly working with Glitch or GitHub?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
	
	Besides the fact that I had changed the frequency of the buttons to “do re me”, colored the buttons from red to violet rainbow colors, and made the game go progressively faster. I would have spent the last few hours changing the background color of the game. I would have changed the color of the title to make it pop. I would have also spent the last few hours trying to add more of the optional features. For example, I would have made the game give the user three chances each time the user gets the pattern incorrect. I would have also added a notification telling the user how many chances the user has before the game terminates.

## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright Youstina Gerges

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

