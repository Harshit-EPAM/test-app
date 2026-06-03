# Quiz CLI

An interactive command-line quiz game built with Node.js. It lets users pick a category, answer multiple-choice questions, and review their results at the end.

## High-Level Description

Quiz CLI is a beginner-friendly terminal application that demonstrates core JavaScript and Node.js concepts such as ES modules, async/await, file handling, and simple object-oriented design. It loads quiz questions from JSON, presents them in the terminal, and tracks the player's score.

## Features

- Interactive terminal-based quiz experience
- Multiple quiz categories
- Selectable question count per round
- Randomized question order
- Score tracking and final results summary
- Review of incorrect answers with correct choices
- Colored terminal output for better readability
- Built with native Node.js modules only, with no external dependencies

## Project Structure

- `index.js` - Application entry point and main game loop
- `quiz.js` - Quiz class and scoring logic
- `input.js` - Readline-based input helpers
- `colors.js` - ANSI color utilities for terminal output
- `questions.json` - Quiz data and categories
- `package.json` - Project metadata and scripts

## Getting Started

### Prerequisites

- Node.js 18 or later
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

   This project does not use external packages, but running `npm install` will create the local lockfile and prepare the project in a standard Node.js workflow.

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
4. Review your score and incorrect answers after the round.
5. Choose whether to play again.

### Available Scripts

- `npm start` - Run the quiz application
- `npm test` - Run Node.js tests using the built-in test runner

## High-Level Description

Quiz CLI is a small terminal quiz game designed to help users practice programming concepts while learning common Node.js patterns. It uses native modules for file reading and terminal interaction, plus a lightweight class-based quiz engine for scoring and progress tracking.
