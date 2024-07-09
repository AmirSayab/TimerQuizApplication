# Awesome Quiz Application

This is a simple and interactive quiz application that allows users to test their knowledge on various topics. The application provides multiple-choice questions, tracks the user's score, and displays the results at the end.
--> URL: https://amirsayab.github.io/TimerQuizApplication/

## Features

- **Multiple-choice questions**: Each question comes with four possible answers, but only one is correct.
- **Timer**: A 15-second timer for each question to add an element of challenge.
- **Score tracking**: The application keeps track of the user's score and displays it at the end of the quiz.
- **Interactive UI**: Provides immediate feedback on the selected answer and highlights the correct answer if the user selects the wrong one.

## Files

- **index.html**: The main HTML file that structures the quiz application.
- **style.css**: The CSS file that styles the quiz application.
- **questions.js**: Contains the quiz questions, options, and correct answers.
- **script.js**: Contains the main logic for the quiz application, including timer functionality, question display, and score calculation.

## How to Use

1. **Start the Quiz**: Click the "Start Quiz" button to begin.
2. **Read the Instructions**: An info box will appear with the quiz rules. Click "Continue" to proceed.
3. **Answer Questions**: Select an answer from the given options. You have 15 seconds to answer each question.
4. **Next Question**: Click the "Next" button to proceed to the next question after selecting an answer.
5. **View Results**: After answering all questions, the results box will display your score.

## Code Overview

### HTML (`index.html`)

The HTML file contains the structure of the quiz application. It includes the start button, info box, quiz box, and result box.

### CSS (`style.css`)

The CSS file styles the quiz application, making it visually appealing and responsive. It uses a combination of flexbox and custom styles for various elements.

### JavaScript

#### `questions.js`

This file contains an array of question objects. Each object includes the question number, question text, answer, and options.

#### `script.js`

This file contains the main logic for the quiz application. It handles the following:

- Displaying questions and options
- Timer functionality
- Score calculation
- Displaying results

Key functions include:

- `showQuetions(index)`: Displays the question and options based on the current index.
- `startTimer(time)`: Starts the countdown timer for each question.
- `optionSelected(answer)`: Handles the user's answer selection and provides immediate feedback.
- `showResult()`: Displays the user's score at the end of the quiz.

## Running the Application

1. **Download or Clone the Repository**: Get the project files on your local machine.
2. **Open `index.html` in a Web Browser**: Simply double-click the `index.html` file to open it in your default web browser.

## Credits

This project was created by Amir Sayab as part of a coding exercise. The application structure and styling are inspired by a tutorial from CodingNepal.

## License

This project is open-source and available under the MIT License. Feel free to use and modify it as per your requirements.

