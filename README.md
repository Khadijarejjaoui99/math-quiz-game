# Math Quiz Console Game

This project is a console-based implementation of a **Math Quiz** game, where players can test their math skills by answering a series of randomly generated math questions. The game allows players to select the difficulty level and operation type, competing against the computer or simply challenging themselves.

---

## Features

- **Interactive Gameplay**: Players answer randomly generated math questions (Addition, Subtraction, Multiplication, or Division).
- **Round-based Gameplay**: Players can choose the number of questions they wish to answer.
- **Difficulty Levels**: Choose between Easy, Medium, Hard, or Mix difficulty levels.
- **Operation Types**: Select between Addition, Subtraction, Multiplication, Division, or Mix operations.
- **Real-time Feedback**: Immediate feedback on whether the answer is correct or wrong.
- **Statistics Summary**: Displays the total number of correct and incorrect answers, along with the final result (Pass or Fail).
- **Replayability**: Players can replay the game as many times as they want.

---

## Concepts Used

- **Enums**:
  - Used to define `enQuestionsLevel` (Easy, Medium, Hard, Mix) and `enOperationType` (Addition, Subtraction, Multiplication, Division, Mix).
- **Structures**:
  - `stQuizData`: Holds the quiz data, including the number of correct and incorrect answers, the number of questions, and the difficulty level and operation type.
- **Functions**:
  - Modular design using functions like `ReadAnswer`, `RandomNumber`, `GenerateQuestion`, and `QuizResult` for better organization and readability.
- **Control Flow**:
  - Loops (`for`, `do-while`) to manage questions and replay functionality.
  - Conditional statements (`if`, `switch`) to determine the operation type, difficulty, and the results.
- **Randomization**:
  - `rand()` is used to generate random numbers and operations.

---

## Technologies Used

- **Language**: C++
- **Libraries**: `<iostream>`, `<cstdlib>`, `<ctime>`

---

## How to Play

1. Clone the repository:

   ```bash
   git clone https://github.com/Khadijarejjaoui99/math-quiz-game.git

   ```

2. Navigate to the directory:
   ```bash
   cd math-quiz-game
   ```
3. Run the executable:

   ```bash
   ./math_quiz

   ```

4. Follow the on-screen instructions to select the number of questions, difficulty level, and operation type, then answer the questions.

## How It Works

### Game Setup:

- The player selects the number of questions they want to answer.
- The player chooses the difficulty level (Easy, Medium, Hard, or Mix).
- The player selects the operation type (Addition, Subtraction, Multiplication, Division, or Mix).

### Gameplay:

- The program generates random math questions based on the selected difficulty level and operation type.
- The player answers each question, and the program provides feedback on whether the answer was correct or incorrect.

### Results:

- After all the questions are answered, the game shows the number of correct and incorrect answers.
- It displays a final result (Pass or Fail) based on the number of correct answers.

### Replay:

- After viewing the results, players can choose to replay the quiz or exit.

## Future Enhancements

- Add more advanced features like time limits or higher difficulty levels.
- Implement a scoring system based on time or answer accuracy.
- Develop a graphical user interface (GUI) for a more interactive experience.
