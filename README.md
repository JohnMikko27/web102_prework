# WEB102 Prework - _Sea Monster Crowdfunding_

Submitted by: **John Mikko Velasquez**

**Sea Monster Games** is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: **16** hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] The introduction section explains the background of the company and how many games remain unfunded.
- [x] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
- [x] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
- [x] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

- [x] List anything else that you can get done to improve the app functionality!
  - I added an "Our Games" button that made the screen go straight to the games container, so that the user doesn't need to scroll all the way down
  - I updated some of the styling and layouts:
    - I increased the font size of the description
    - I added a hover and click effect on the buttons in the button container: on hover they change color and get bigger, and on click they get smaller to make the impression that they were clicked
    - I added a box shadow to each game card so that they pop out more and are more distinguishable
    - I added flex to each game card so that the title and text aren't too jumbled up and it is much easier to read
    - I made the title of each game in each game card bigger and made it bold so that it stands out more
    - I also added changed the layout of the cards from flex to grid. And I used auto-fill so that every time there is space available for a new card, it will act like there is a card there and shift everything. I find this to look better because everything (the game cards) is nice and aligned.

## Video Walkthrough

Here's a walkthrough of implemented features:

<img src='./assets/web102-video-walkthrough.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

<!-- Replace this with whatever GIF tool you used! -->

GIF created with Kap

<!-- Recommended tools:
[Kap](https://getkap.co/) for macOS
[ScreenToGif](https://www.screentogif.com/) for Windows
[peek](https://github.com/phw/peek) for Linux. -->

## Notes

Describe any challenges encountered while building the app.

- I had challenges in using the spread operator. I thought I knew how it worked, but implemnting and using it was a different thing.
- Another challenge I had was using the ternary operator inside a template string. All this time I have only been using the template string to add variables into my string, but I never realized that you can use other javascript syntax. As a result, using the ternary operator in the template string got me a bit stuck, especially with the logic of getting the grammar right.
- I had issues doing the gif video walkthrough because github doesn't let users upload files that are more 100mb and mine was initially 700mb. So I kept redoing the gifs, decreasing the fps, the length, etc. so that I could get a gif file size of less than 100mb

## License

    Copyright [2023] [John Mikko Velasquez]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
