# Little Professor

---

## Description

The **Little Professor** program is a Python-based math quiz generator inspired by a childhood toy. It challenges users with 10 randomly generated addition problems at a difficulty level of their choosing. The program is interactive, tracks the user’s score, and provides corrective feedback when answers are incorrect.

Key features include:

- **Difficulty Levels**: Users can select a difficulty level (1, 2, or 3) to adjust the range of numbers used in the math problems.
- **Error Feedback**: The program provides "EEE" feedback for incorrect answers and reveals the correct answer after three failed attempts.
- **Score Tracking**: Displays the user's score out of 10 after completing all problems.
- **Robust Input Handling**: Ensures user inputs are valid and prompts for re-entry if they are not.

---

### Files

#### `professor.py`
The main Python script for the program, structured to:

- Prompt the user to select a difficulty level (1, 2, or 3).
- Randomly generate 10 math problems based on the selected difficulty.
- Allow users three attempts to answer each problem correctly, displaying feedback for incorrect answers and showing the correct answer if all attempts are used.
- Calculate and display the user's final score after all questions.

---

### Design Choices

#### User Interaction
The program engages users with interactive prompts, providing a clear and intuitive way to answer math problems. Feedback for incorrect answers helps reinforce learning.

#### Difficulty Levels
The inclusion of difficulty levels (1, 2, and 3) makes the program suitable for various skill levels, from beginners to advanced users.

#### Error Handling
To ensure a smooth user experience, the program includes error handling for invalid inputs, such as non-integer answers or unsupported difficulty levels.

---

### How to Run

1. Install Python 3.x.
2. Save `professor.py` to your desired directory.
3. Run the program in your terminal:
   ```bash
   python professor.py```
4. Follow the prompts to select a difficulty level and solve the math problems.


### Future Improvements
- Expanded Operations: Include subtraction, multiplication, and division for greater variety.
- Timed Challenges: Introduce a timer to increase difficulty and track completion times.
- Persistent Scores: Allow users to save and review their scores across sessions.
- GUI: Add a graphical user interface for enhanced interactivity.
