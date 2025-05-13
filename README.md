# Little Professor - Python Math Quiz App

![Little Professor](https://anythinginparticular.co.uk/wp-content/uploads/2018/10/P1270742.jpg)

---

## Description

The **Little Professor** program is a Python-based math quiz generator inspired by the iconic childhood toy. It presents users with 10 randomly generated addition problems, offering an engaging and educational experience tailored to different skill levels.

Designed for simplicity, interaction, and learning reinforcement, the app includes real-time feedback, score tracking, and adjustable difficulty settings.

Key features include:

- **Difficulty Levels**
Users can choose from levels 1, 2, or 3, which scale the number ranges for each problem.
- **Error Feedback**
Users receive "EEE" feedback for incorrect answers and are shown the correct answer after three failed attempts.
- **Score Tracking**
After 10 problems, the program displays the user’s final score out of 10.
- **Robust Input Handling**
Gracefully handles invalid input (e.g., non-integers or unsupported difficulty levels) and prompts re-entry.

---

### Files Overview

`professor.py` - The main Python script handles:
- Prompting for difficulty level
- Generating and presenting 10 random addition problems
- Allowing up to 3 attempts per problem
- Providing instant feedback and showing correct answers
- Calculating and displaying the final score

---

### Design Choices

#### User Interaction
Clear prompts and feedback make the app easy to use for all ages.

#### Difficulty Levels
Difficulty levels support different age groups or learner stages.

#### Error Handling
Validates all inputs to prevent crashes and confusion.

---

### How to Run

1. Install **Python 3.x**
2. Save `professor.py` to your desired directory
3. Run the program in your terminal:
   ```bash
   python professor.py
4. Follow the prompts to select a difficulty level and complete the quiz


### Future Improvements
- Expanded Operations: Support for subtraction, multiplication, and division
- Timed Challenges: Timed challenges for increased difficulty
- Persistent Scores: Persistent scores for tracking progress
- GUI: GUI version for enhanced accessibility
