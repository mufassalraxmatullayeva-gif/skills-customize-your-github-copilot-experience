
📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build a command-line Hangman game in Python that lets a player guess letters to reveal a hidden word before they run out of attempts. This exercise practices string manipulation, control flow, user input handling, and simple program design.

## 📝 Tasks

### 🛠️  Build the Hangman game

#### Description
Create a playable, well-structured Hangman game that runs in the terminal. The program should be user-friendly and robust to common input mistakes.

#### Requirements
Completed program should:

- Randomly select a word from a predefined list (or bundled word list).
- Prompt the player to guess one letter at a time and display the current progress using placeholders (e.g., _ _ a _ _ ).
- Track and display letters already guessed (both correct and incorrect).
- Limit the number of incorrect guesses (lives) and clearly show remaining attempts.
- Prevent counting repeated guesses against the player.
- End the game with a clear win message when the word is fully guessed or a lose message when attempts are exhausted, revealing the correct word.
- Be case-insensitive for letter input (treat 'A' and 'a' the same).
- Include a small `starter-code.py` in the assignment folder to help students get started (boilerplate input loop and word list is acceptable).

Example interaction (simplified):

```
Word: _ _ _ _ _
Guesses left: 6
Guessed letters: a, e
Enter a letter: o
Correct! Word: _ o _ _ _
```

### 🛠️  Enhancements (optional)

#### Description
Add one or more extra features to make the game more polished or challenging.

#### Requirements (pick any):

- Load words from an external text file (e.g., `words.txt`) so teachers can customize the list.
- Add a hint feature (reveal one letter or show word category).
- Show ASCII-art hangman that progresses as incorrect guesses accumulate.
- Keep a simple high-score table or best completion time in a local file.
- Add difficulty levels that control word length or number of attempts.

---

Place any starter code or assets in this assignment folder (`starter-code.py`, sample `words.txt`, etc.).

Good luck — keep the interface clear and focus on handling edge cases (invalid input, repeated guesses, empty word list).
