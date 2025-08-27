**1. Description**
A Python implementation of the classic Hangman game, where the user must guess the letters of a randomly chosen word before running out of lives. The game features visual feedback using ASCII art and keeps track of correct guesses and remaining lives. The code uses separate files for the word list and ASCII art stages.

**2. How It Works**
The program imports a list of words and ASCII art stages from separate Python files.

At the start, a word is randomly selected as the target word and the initial game logo is displayed.

The player repeatedly guesses one letter at a time.

Correct guesses reveal letters in the word; incorrect guesses decrease available lives and display new stages.

The game ends when the player guesses all letters or loses all lives.


**3.Operators and Functions Used**

Operators:

= (Assignment): Assigns values to variables (e.g., lives, chosen_word, correct_letters, placeholder).

+ (Concatenation): Adds strings together, e.g., building up the display string.

in: Checks for membership in lists or strings (e.g., letter in word, guess in correct_letters).

not: Logical negation, used in game loop conditions.

==: Comparison to check for equality.


Functions and Methods:

print(): Displays game information, including the logo, current state, and results.

input(): Takes user guesses as input.

random.choice(): Selects a word at random from the list.

.lower(): Ensures user input is case-insensitive.

range(): Generates a sequence for for-loops.

len(): Returns the length of the word for initialization.
-= (Subtraction assignment): Decreases the number of lives when the user makes a wrong guess.

[] (Indexing): Accesses elements in lists and strings, such as stages[lives] and iterating through chosen_word.
