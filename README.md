
# Quiz Generator

## Overview
This project is a simple quiz generator built using HTML, CSS, and JavaScript. It allows users to take a quiz by answering multiple-choice questions. After submitting their answers, users receive feedback on their performance, including their score and correct answers.

## Features
- **Multiple-Choice Questions:** The quiz consists of multiple-choice questions with several possible answers.
- **Immediate Feedback:** Users receive their score and a breakdown of correct and incorrect answers immediately after submitting the quiz.
- **Customizable Questions:** Questions and answers can be easily customized in the JavaScript file.

## How It Works
1. **HTML:** 
   - Defines the structure of the quiz, including the questions, answer choices, and submission button.

2. **CSS:** 
   - Styles the quiz to make it visually appealing and easy to navigate. Includes layouts for the questions, answer choices, and results display.

3. **JavaScript:** 
   - Handles the logic for generating the quiz, evaluating user responses, and calculating the final score. 
   - Provides immediate feedback by highlighting correct and incorrect answers and displaying the final score.

## Files Included
- `index.html`: The main HTML file containing the quiz structure.
- `styles.css`: The CSS file for styling the quiz interface.
- `script.js`: The JavaScript file that manages quiz logic, including question generation, answer evaluation, and scoring.

## Usage
1. Open `index.html` in a web browser.
2. Answer each quiz question by selecting the correct answer from the available choices.
3. After completing the quiz, click the "Submit" button.
4. Your score and feedback will be displayed, showing which questions you got right and which you got wrong.

## Example
- **Question:** What is the capital of France?
  - **Choices:** 
    1. Berlin
    2. Madrid
    3. Paris
    4. Rome
- **User Selection:** Paris
- **Feedback:** Correct! Your score: 1/1

## Customization
- **Add or Remove Questions:** Edit the `questions` array in `script.js` to add or remove questions.
- **Change Quiz Style:** Modify `styles.css` to change the appearance of the quiz, including colors, fonts, and layouts.
- **Update Answer Logic:** Adjust the answer checking logic in `script.js` to accommodate different types of questions or scoring systems.

## Complexity
- The quiz operates with a linear time complexity, evaluating each question in constant time relative to the number of questions.

## Technologies Used
- **HTML**
- **CSS**
- **JavaScript**


