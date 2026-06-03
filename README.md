# Quiz CLI

An interactive command-line quiz game built with Node.js. It lets users choose a category, answer multiple-choice questions, and review their results at the end.

## High-Level Description

Quiz CLI is a beginner-friendly terminal application for practicing JavaScript, Node.js, and general programming concepts. It loads questions from a JSON file, displays a quiz in the terminal, tracks the score, and shows feedback after each round.

The app is written using native Node.js modules and ES modules, making it a compact example of modern JavaScript CLI development.

## Features

- Interactive terminal-based quiz experience
- Multiple quiz categories
- Choose how many questions to answer per round
- Randomized question order
- Score tracking and final results summary
- Review of incorrect answers with the correct answers
- Colored terminal output for improved readability
- Built with built-in Node.js modules only

## Project Structure

- `index.js` - Application entry point and main game loop
- `quiz.js` - Quiz class, scoring logic, and results display
- `input.js` - Readline-based input helpers for prompts and selections
- `colors.js` - ANSI color utilities for terminal output
- `questions.json` - Quiz data and categories
- `package.json` - Project metadata and scripts

> Note: The source code imports modules from `./src/` and loads questions from `data/questions.json`. If you reorganize the files, keep the paths in sync with the code.

## Getting Started

### Prerequisites

- Node.js 18 or later
- npm (included with Node.js)

### Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd test-app
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

   This project has no external dependencies, but running `npm install` is still a good way to set up the local Node.js environment.

### Run the Quiz

Start the application with:

```bash
npm start
```

Or run it directly:

```bash
node index.js
```

### How to Play

1. Choose a quiz category.
2. Select how many questions you want to answer.
3. Enter the option number for each question.
4. Review your score and any incorrect answers.
5. Choose whether to play again.

### Available Scripts

- `npm start` - Run the quiz application
- `npm test` - Run Node.js tests using the built-in test runner
