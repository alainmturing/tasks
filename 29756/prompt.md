Create a browser based target tapping game. The goal of the game is to tap appearing targets as quickly as possible within a time limit to earn points.

Game should always start at level selection screen. User should be able to restart when they lose and go back to level selection.

Key Features:

Controls: Mouse clicks on targets.
Targets: Targets should spawn every 2 seconds.
Levels: Decreasing the time a target spends on the screen before disappearing for Easy, Medium, Hard. For easy, targets spend 3.5 seconds on the screen, for medium -2.5, for hard - 1.5
Score: Increment points differently for each level. +10 points for each target hit for Easy, +20 for Medium, +30 for Hard, -10 for misses. Prominently displayed at the top center of the screen along with timer.
Time Limit: We will set a time limit of 20 seconds. When the user successfully taps a target, they get +1 second added to their time limit and are shown with an animation of the current timer and +1 popping up in the center of the score/time limit.
Rules: Game ends if user reaches below 0, or run out of time.
Graphics: Simple circle svg outlines with a red dot in the center and a white background. Game background should be a grey gradient.
Sound: Tapping sounds for hits.

Requirements:
- Single HTML file containing HTML, CSS, and JavaScript
- SVG for target graphics
- Sound effects using WebAudio Api