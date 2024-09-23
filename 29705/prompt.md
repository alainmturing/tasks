Design a browser-based bubble popping game where players pop bubbles by clicking on them before they reach the top of the screen. The game should be visually appealing and interactive.

Key Features:

- Controls: Mouse clicks to pop bubbles.
- Levels: Different difficulty levels (Easy, Medium, Hard) Level selection should happen first before game start.
- Level Description: 
    - Easy - Bubbles with number of clicks required to pop spawn randomly requiring between 1-2 clicks to pop
    - Medium - Bubbles with number of clicks required to pop spawn randomly requiring between 2-3 clicks to pop
    - Hard - Bubbles with number of clicks required to pop spawn randomly requiring between 3-4 clicks to pop
- Bubbles: Number of clicks required to pop displayed in the center of each bubble
- Score: +5 per bubble popped, -10 if a bubble reaches the top. User score should not be able to go below 0.
- Game Rule: Game ends if user fails to pop 3 bubbles in a row. Everytime they successfully pop a bubble, their lives reset.
- Graphics: Colorful bubbles with a simple background. Prominently display number of lives at all points throughout the game.
- Sound: Popping sounds when bubbles are clicked.

Requirements:
- Single HTML file containing HTML, CSS, and JavaScript
- SVG for any graphics
- Sound effects for bubble pops using WebAudio Api