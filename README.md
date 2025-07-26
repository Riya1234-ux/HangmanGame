# 🕹️ Hangman Game in Python

Welcome to the classic *Hangman Game*, built using Python. This is a simple terminal-based word guessing game where you try to guess the word one letter at a time before the man is "hanged"!

## 📌 Features

* Single-player terminal game
* Random word selection
* Word and letter display after each guess
* Tracks correct and incorrect guesses
* ASCII art representation of the Hangman

## 🛠️ Requirements

* Python 3.x

No external libraries required.

## 🚀 How to Run

1. Clone this repository or download the .py file.

bash
git clone https://github.com/your-username/hangman-python.git
cd hangman-python


2. Run the script:

bash
python hangman.py


## 🎮 How to Play

* The computer will randomly select a word.
* You will guess one letter at a time.
* If the letter is in the word, it will be revealed in the correct position.
* If the letter is not in the word, a part of the hangman is drawn.
* You have a limited number of wrong guesses before the game ends.

## 🧠 Example Gameplay


Word: _ _ _ _ _
Guess a letter: e
Correct!
Word: _ e _ _ _
Guess a letter: a
Wrong guess! You have 5 tries left.


## 📂 File Structure


hangman-python/
│
├── hangman.py       # Main game file
├── words.txt        # (Optional) Word list file
└── README.md        # Project description
