# Hangman Game


Welcome to the **Hangman Game**! This is a simple Python implementation of the classic word-guessing game. The goal is to guess the hidden word before you run out of lives. Each incorrect guess brings you closer to losing, so choose your letters wisely!

<i>Example of how the program works</i>
<img width="468" alt="Screenshot 2025-02-12 at 22 03 20" src="https://github.com/user-attachments/assets/a888cd39-f18d-4223-8646-cc7c23762caa" />

<i>Example of how the program ends</i>
<img width="383" alt="Screenshot 2025-02-12 at 22 04 06" src="https://github.com/user-attachments/assets/fb34c316-8de2-4c64-9a05-f40851e82b79" />

## How to Play

1. **Run the Script**: Execute the Python script to start the game.
2. **Guess a Letter**: You will be prompted to guess a letter. Type a single letter and press Enter.
3. **Feedback**: 
   - If the letter is in the word, it will be revealed in the correct position(s).
   - If the letter is not in the word, you will lose a life.
4. **Win or Lose**: 
   - You win if you guess all the letters in the word before running out of lives.
   - You lose if you run out of lives before guessing the word.

## Installation

To run this game, you need to have Python installed on your system. You can download Python from [python.org](https://www.python.org/).

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/hangman-game.git
   cd hangman-game
   ```

2. **Install Dependencies**:
   There are no external dependencies required for this game.

3. **Run the Game**:
   ```bash
   python hangman.py
   ```

## Code Structure

The game is structured into several parts:

- **hangman_words.py**: Contains the list of words that can be chosen for the game.
- **hangman_art.py**: Contains the ASCII art for the game logo and the hangman stages.
- **hangman.py**: The main script that runs the game.

### Main Script (`hangman.py`)

The main script handles the game logic, including:

- Selecting a random word from the word list.
- Displaying the current state of the word with blanks for unguessed letters.
- Handling user input and updating the game state.
- Displaying the hangman stages based on the number of lives remaining.
- Determining if the player has won or lost.

### TODO List

The script includes several TODOs that you can implement to enhance the game:

1. **TODO-1**: Update the word list to use the `word_list` from `hangman_words.py`.
2. **TODO-2**: Import the stages from `hangman_art.py` and display them based on the number of lives remaining.
3. **TODO-3**: Import the logo from `hangman_art.py` and print it at the start of the game.
4. **TODO-4**: If the user enters a letter they've already guessed, print the letter and let them know.
5. **TODO-5**: If the letter is not in the chosen word, print out the letter and let them know it's not in the word.

## Contributing

Feel free to contribute to this project by forking the repository and submitting pull requests. You can also open issues for any bugs or feature requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Enjoy playing the Hangman Game! 🎮
