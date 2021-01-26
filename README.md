
<img src="https://github.com/p3hndrx/B-B-Shuffle/blob/main/App/img/bb-logo.png" width="500px"
     alt="BackDoors & Breaches"
     style="float: left; margin-right: 10px;" />

# B&B-Shuffle
Dashboard for conducting [Backdoors and Breaches](https://www.blackhillsinfosec.com/projects/backdoorsandbreaches/) sessions over Zoom.

Backdoors and Breaches is the property of [BlackHills InfoSec](https://www.blackhillsinfosec.com/), but is great for conducting incident response walkthroughs and training seminars.

# About This Script
This is a simple HTML page, best viewed at 1920x1080.

Consists of HTML, CSS, and JS to control basic behaviors.

## Features:
- Dice Roll
- Card Shuffle
- Injects
- Floating Counters

# How it Works
When you reload the page, you will get:
- 4x Scenario Cards (Top)
- 4x Randomly Assigned Established Procedures (2nd Row)
- 6x Randomly Assigned Remaining Procedures

There will be a dice box at the bottom, an Inject card dealer, and 3x stacked tokens for marking.
As the DM, you will get the solution to the Scenario (popup at bottom right).

<img src="https://github.com/p3hndrx/B-B-Shuffle/blob/main/Screenshots/dashboard.png" width="900px"
     alt="Dashboard"
     style="float: left; margin-right: 10px;" />

## NOTES: 
- Once you click the scenario card to reveal, you cannot flip it back.
- There are 2 buttons for rolling Established Procedures and Other Procedures (respectively)
- The totals and success/failure of the Dice Roll is calculated in the Game Progress box
<img src="https://github.com/p3hndrx/B-B-Shuffle/blob/main/Screenshots/roll.png" width="500px"
     alt="Dashboard"
     style="float: left; margin-right: 10px;" />


- All cards activate the lightbox.
<img src="https://github.com/p3hndrx/B-B-Shuffle/blob/main/Screenshots/card-display.png" width="500px"
     alt="Dashboard"
     style="float: left; margin-right: 10px;" />

- Chips can be dragged onto procedure cards to denote they are deactivated for x # of turns
<img src="https://github.com/p3hndrx/B-B-Shuffle/blob/main/Screenshots/chips.png" width="500px"
     alt="Dashboard"
     style="float: left; margin-right: 10px;" />


## Scripts/Snippets/Tutorials Referenced
- [Flip Cards with Javascript](https://www.ricardomoreira.io/blog/2020-06-15-flip-cards-with-javascript/) by Ricardo Moreira
- [How to Create a Draggable Div](https://www.w3schools.com/howto/howto_js_draggable.asp) by W3Schools
- [How to Randomize (shuffle) a Javascript Array](https://stackoverflow.com/questions/2450954/how-to-randomize-shuffle-a-javascript-array) via Stackoverflow
- [Lightbox](https://lokeshdhakar.com/projects/lightbox2/) by Lokesh Dhakar. (+[JQuery](https://jquery.com/))
- [Google Fonts](https://fonts.google.com/)
- And of course, the great folks over at [BlackHills InfoSec](https://www.blackhillsinfosec.com/) for the art assets.

<img src="https://github.com/p3hndrx/B-B-Shuffle/blob/main/App/img/blackhills-logo.png" width="200px"
     alt="BlackHills InfoSec"
     style="float: left; margin-right: 10px;" />
