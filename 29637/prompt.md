Design a browser-based word guessing game where players try to guess a hidden word by suggesting letters. The game should be visually appealing and interactive.

Game features:
- A selection of word categories (e.g., animals, countries, foods)
- Three difficulty levels: easy (longer words, more guesses), medium, and hard (shorter words, fewer guesses)
- Visual representation of the hangman or a creative alternative
- On-screen keyboard for letter selection where user can click on letter or use their keyboard and if they use their keyboard or click on a key, it should do some sort of animation.
- Hint system that reveals a letter or gives a clue about the word

Game rules:
- Player selects a category and difficulty level
- The game randomly selects a word from the chosen category
- Player gets a limited number of incorrect guesses based on difficulty
- Correct letter guesses reveal all instances of that letter in the word
- Incorrect guesses progress the visual representation (hangman or alternative)
- Game ends when the word is guessed or when out of guesses

Requirements:
- Single HTML file containing HTML, CSS, and JavaScript
- SVG graphics for the hangman or alternative visual representation
- Animations for letter reveals and game progression
- Sound effects for correct and incorrect guesses (Utilize WebAudio API)
- A scoring system based on difficulty and remaining guesses
- Option to play again with a new word after each game