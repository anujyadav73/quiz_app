# Quick Quiz

Quick Quiz is a simple web-based quiz application that allows users to test their knowledge with multiple-choice questions. Users can play the quiz, view their scores, and save their high scores.

## Project Structure

```
app.css
end.html
end.js
game.css
game.html
game.js
highscores.css
highscores.html
highscores.js
index.html
questions.json
```

## Getting Started

To get started with the Quick Quiz application, follow these steps:

1. Clone the repository to your local machine.
2. Open the project directory in your preferred code editor (e.g., Visual Studio Code).
3. Open `index.html` in a web browser to start the application.

## Files Overview

- `index.html`: The main entry point of the application. It contains links to start the quiz and view high scores.
- `game.html`: The quiz interface where users answer multiple-choice questions.
- `end.html`: The end screen where users can save their scores.
- `highscores.html`: The high scores screen where users can view saved high scores.
- `questions.json`: A JSON file containing the quiz questions and answers.
- `app.css`: The main stylesheet for the application.
- `game.css`: Styles specific to the quiz interface.
- `highscores.css`: Styles specific to the high scores screen.
- `end.js`: JavaScript for handling the end screen and saving scores.
- `game.js`: JavaScript for handling the quiz logic and fetching questions.
- `highscores.js`: JavaScript for displaying high scores.

## How to Play

1. Open `index.html` in a web browser.
2. Click the "Play" button to start the quiz.
3. Answer the multiple-choice questions within the quiz interface.
4. After completing the quiz, you will be redirected to the end screen where you can save your score.
5. Enter your username and click "Save" to save your score.
6. View the high scores by clicking the "High Scores" button on the main screen.

## Dependencies

This project does not have any external dependencies. All necessary files are included in the project directory.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- The quiz questions are fetched from the Open Trivia Database (https://opentdb.com/).
