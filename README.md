# hangman_project
This is a simple command-line Hangman game built using Python. The game randomly selects a word, and the player has to guess it one letter at a time before they run out of lives.
📁 File Structure
main.py – Main game logic.

hangman_words.py – Contains a list of possible words to guess.

hangman_art.py – Contains ASCII art for game visuals like stages and logo.

💡 Features
Random word selection from a pre-defined word list.

Tracks user guesses and prevents duplicate guessing.

Reduces lives on incorrect guesses and shows corresponding hangman stage.

Displays visual ASCII art for better user experience.

Ends game with win/lose message and reveals the correct word.

 Game Logic Breakdown:
The game begins by displaying a logo (imported from hangman_art.py).

A word is randomly selected from the word_list in hangman_words.py.

The player is shown placeholders (_) representing each letter of the word.

The player inputs one letter at a time to guess the word:

If the letter is correct, it replaces the placeholder.

If the letter is incorrect, the player loses a life.

The game keeps track of correct guesses and already guessed letters.

The game ends when:

The player guesses all letters correctly – YOU WIN

The player loses all 6 lives – YOU LOSE, and the correct word is revealed.

 Sample Output
python-repl
Copy
Edit
_ _ _ _ _
Guess a letter: e
Word to guess: _ _ e _ _
4/6 LIVES LEFT
...
YOU WIN 🎉
 TODOs Implemented
 Updated to use the external word_list.

 Displayed logo at the start of the game.

 Warns on duplicate guesses.

✅ Reduces lives on wrong guesses and prints visual stages.

✅ Displays win/loss message with correct word.


