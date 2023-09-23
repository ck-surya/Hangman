# Hangman
# JavaScript-Project
basic JavaScript and ES6-2015 for command-line practice 
Objective:
The objective of the Hangman game is for the player to guess a hidden word by suggesting letters within a certain number of attempts. The game continues until the player successfully guesses the word or runs out of attempts.

Game Components:

Word to Be Guessed: One player thinks of a word and keeps it secret from the other player(s). This is the word that needs to be guessed.

Hint (Optional): The player who thought of the word may provide a hint to give the guessing player(s) a clue about the word's meaning or category.

Game Board: A representation of the word being guessed, with empty spaces for each letter. Initially, all spaces are usually represented by underscores "_".

Alphabet: A list of available letters that can be guessed. As the player makes guesses, the guessed letters are crossed out or marked as used.

Hangman Figure: A series of illustrations (typically ASCII art) representing a hanging man. The figure is drawn step by step as the player makes incorrect guesses.

Gameplay:
The gameplay of Hangman proceeds as follows:

The player making the word selects a word and, optionally, provides a hint.

The game board is prepared with empty spaces for each letter of the word and a hangman figure.

The guessing player(s) take turns suggesting letters.

If the suggested letter is in the word, it is placed in the corresponding empty space(s), revealing part of the word.

If the suggested letter is not in the word, a part of the hangman figure is drawn as a penalty.

The game continues until one of the following conditions is met:

The guessing player(s) successfully guess the word by filling in all the spaces.
The hangman figure is fully drawn, indicating that the guessing player(s) have run out of incorrect guesses.
If the word is successfully guessed, the player(s) win the game. If the hangman figure is fully drawn, they lose.

Winning and Losing:

Winning: The game is won when the guessing player(s) successfully guess the word by filling in all the spaces. They may receive a score or reward based on the number of incorrect guesses.

Losing: The game is lost if the hangman figure is fully drawn before the word is guessed. In this case, the player(s) lose the game.

Hangman is a fun and challenging word game that tests vocabulary, deduction skills, and word-guessing abilities. It can be played with friends, family, or as a solo game.



