# CodeAlpha_hangman_game
🪢 Hangman Game (Python)

A beginner-friendly text-based Hangman game built in Python.
The player tries to guess a hidden word one letter at a time, with only 6 chances to make mistakes before the game ends.

This project demonstrates the use of Python basics such as random, while loops, conditionals, lists, and strings — making it a perfect mini-project for learners.

📖 Table of Contents

Features

Game Rules

Project Structure

Installation & Setup

How to Play

Example Gameplay

Screenshots (ASCII Art)

Future Improvements

License

🎮 Features

✔ Predefined list of 5 words (no external files needed)
✔ Random word selection for each game
✔ Tracks guessed letters and prevents duplicates
✔ Validates inputs (only single alphabet characters allowed)
✔ Up to 6 incorrect guesses allowed
✔ Beginner-friendly, fully text-based

📝 Game Rules

The computer randomly chooses a word from a predefined list.

The player must guess the word one letter at a time.

Each wrong guess decreases the remaining chances.

If the player makes 6 incorrect guesses, the game ends.

If the player correctly guesses all letters before running out of tries, they win.

📂 Project Structure
hangman/
│── hangman.py    # Main game script
│── README.md     # Documentation

⚙ Installation & Setup

Clone the repository:

git clone https://github.com/your-username/hangman.git
cd hangman


Run the game:

python hangman.py


✅ No extra dependencies required (only Python 3.x).

🎲 How to Play

The game will show the word as underscores (_) at the beginning.

Type a letter and press Enter to guess.

Correct letters will be revealed in their positions.

Wrong guesses will reduce your attempts.

The game ends when you either:

Guess all letters correctly 🎉

OR run out of 6 chances 💀

💻 Example Gameplay
Welcome to Hangman!
You have 6 chances to guess the word.

Word:  _ _ _ _ _
Wrong guesses left: 6
Guess a letter: a
✅ Correct!

Word:  a _ _ _ _
Wrong guesses left: 6
Guess a letter: z
❌ Wrong guess!

Word:  a _ _ _ _
Wrong guesses left: 5
...

🖼 Screenshots (ASCII Art)

If you want to make it more fun, you can add ASCII art for each wrong guess stage, for example:

Stage 0 (Start):       Stage 3:           Stage 6 (Game Over):

  +---+                +---+              +---+
  |   |                |   |              |   |
      |                O   |              O   |
      |               /|\  |             /|\  |
      |               /    |             / \  |
      |                    |                  |
=========            =========          =========

🚀 Future Improvements

Add difficulty levels (easy/medium/hard)

Load words from a larger dictionary file or API

Multiplayer mode (one player enters a word, the other guesses)

GUI version using Tkinter or PyQt

Web-based version with Flask/Django
