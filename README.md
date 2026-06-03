# Quiz CLI

## High-Level Description

Quiz CLI is an interactive command-line quiz game built with Node.js and ES modules. It lets users choose a quiz category, answer multiple-choice questions, and receive a final score with feedback at the end.

The project is designed as a beginner-friendly example of modern JavaScript concepts such as async/await, classes, file handling, and terminal input/output.

## Features

- Interactive terminal-based quiz experience
- Multiple quiz categories, including:
  - JavaScript Basics
  - Node.js Fundamentals
  - General Programming
- Option to play all questions or a smaller set
- Randomized question order for each quiz session
- Score tracking and percentage-based results
- Review of incorrect answers after the quiz
- Colored terminal output for better readability
- No external dependencies required

## Project Structure

```text
.
├── colors.js        # ANSI color helpers for terminal output
├── index.js         # Application entry point
├── input.js         # Readline-based input utilities
├── questions.json   # Quiz categories and question data
├── quiz.js          # Quiz logic and scoring
├── package.json     # Project metadata and scripts
└── README.md        # Project documentation
```

## Getting Started

### Prerequisites

- Node.js 18 or higher
- npm (comes with Node.js)

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

This project does not currently use third-party packages, but running `npm install` will prepare the project for standard Node.js workflows.

### Running the Quiz

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
3. Enter the number of the answer you think is correct.
4. Review your final score and incorrect answers.
5. Choose whether to play again.

### Testing

Run the test command with:

```bash
npm test
```

> Note: The project is set up to use Node's built-in test runner. Add test files as needed to expand coverage.

## Notes

- The quiz data is stored in `questions.json`.
- Terminal colors are implemented using ANSI escape codes, so no extra library is required.
- The app uses ES modules, so imports use `import` / `export` syntax.
