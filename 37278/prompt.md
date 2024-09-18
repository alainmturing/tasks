Create a browser-based rhythm game where notes fall from the top and the user must match a,s,d,f key to the note lined up with that key.
 Initially, the user can select from one of 3 levels, easy, medium, hard, which will determine the speed of the falling notes. The user can click on start game. Once the game starts, the user sees their score on the top right. The user must see a straight line above all the keys which are columnized and separated. The notes should fall down in line with the keys (a,s,d,f). A correct hit is when the user hits the key as the note falls on the line. If the note passes the line, it counts as a miss. The game should run indefinitely or until the user loses. I will define this more in the game rules below:
Game rules:
- The user starts with 0 points
- Each missed key deducts 5 points from the user’s score
- Each key hit adds 5 points to the user’s score
- If the user’s score reaches -20 points, the game ends and they can choose to restart or select a new level. If they choose to select a new level, we reset to the beginning where we select level and start game. If we choose to just restart, it restarts with the same level (speed) configuration.
- If the user hits the key without there being a note to hit, it counts as a miss and we should deduct 5 points.
I have these requirements:
- Single HTML file containing HTML, CSS, JavaScript, SVG, and Web Audio API code
- Notes falling from the top of the screen
- Keyboard input (A, S, D, F) to match falling notes
- Sound effects for correct note hits
- Score counter and combo system
- SVG graphics for notes and background
- Make it visually appealing
- Make sure A, S, D, F has a distinct shape falling for that column. 
- Make sure the shape disappears when it’s successfully hit or miss and plays a distinct sound for it.