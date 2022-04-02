# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Shuyan Yan

Time spent: 6 hours spent in total

Link to project: (insert your link here, should start with https://glitch.com...)
https://glitch.com/edit/#!/polite-earthy-humerus

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

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![Lose](https://user-images.githubusercontent.com/76415280/161353368-89a500c7-dd98-4de5-afee-e2453dc48026.gif)

![Win](https://user-images.githubusercontent.com/76415280/161352154-51fc3a5c-26d6-4575-bb88-634dd5a10d53.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
* I did not use any outside resources to help me complete my submission.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
* When I was trying to do the guess function. I came up with the outest if-else statement quickly but I had some difficulty in understanding the difference between “Is turn over” and “Is this the last turn”. Because of that, I found it challenging to come up with the code on my own for the rest of two if-else statements. I wasn’t very clear about how to differentiate between users finishing guessing for a specific clue sequence and the program finishing playing all the clue sequences. To help me fully grasp the logic, I peeked at the solution provided and tried to see how it matched with the flow chart one by one. Then I finally understood the logic. 
* I also had some trouble understanding the github tutorials at the beginning. The video tutorial taught us to download a desktop app for github and I tried to download it. However, I could not edit my README file on the desktop app. I was confused about the difference between the desktop app and the online web app, and I was thinking if I could just use the online app to finish the steps required. Then I tried and I found out that I could easily edit the README file using the online app and also finish the remaining tasks such as copying the GIF links as well as merging my Glitch link. 
* When following the tutorials to create the GIF, I am a bit confused. It says at the first line that “Create a gif of your app using LICEcap or Recordit.” but the next line instructs us to either create a GIF using QuickTime or Using Recordit. I was hesitant about which one to choose as I was thinking if LICEcap and QuickTIme are the same thing. It was a very minor challenge, and I overcame it by clicking the three links to glance at which one seems the most efficient to follow. I chose QuickTime and it worked really well.


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
* I feel like it was easy and straightforward to follow the steps, but I was wondering how easy it is for me to come up with everything on my own. On what level or how many prior experiences do I need so that I could remember all the syntax and know what to apply and what resources to refer to when trying to build everything on my own? Also, On what level will I be able to generally evaluate a specific web development project in terms of its difficulty, average time to build it? 
* There could be so many projects related to web development. What kind of projects beginners can start building to try to learn the basics or is it okay to start building whatever website I want to build such as an online ordering app, etc.? 
When I want to build a new website, where should I start? Also,  Should I try to find existing open resources that might be similar to my projects or I should think very hard by ourselves first.
* How would my other CS classes help my web development skill? I hear a lot of people saying that web development is very different and you don’t need to have much coding experience before. I wonder if that is true and will my other CS classes such as data structures, functional programming help my web development? Also, how many overlaps web development has with our introductory CS course?


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
* I am thinking about spending some time making this project more music related. For example, as a piano player, I want to add some features and edit the current functions to make it a simple online piano. I will make the buttons black and white to simulate a simple piano keyboard (From C to B). Including all the white and black notes, I will need to put 17 buttons and I can adjust their sizes to make them look like piano keys. I have to make sure they are put in a single row. I will try to find the corresponding sound for each key, either finding a soundtrack file or just to change the freqMap value directly since each button (key) will still have only one sound. For the pattern, I can define it with a piano piece which sounds pleasant. When the program plays a sequence of cues, it will actually play that small piece of piano music. This app will not only train users' memories but also help them to remember a small piano piece. 




## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.youtube.com/watch?v=3vbf7bWY5kk)


## License

    Copyright [Shuyan Yan]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
