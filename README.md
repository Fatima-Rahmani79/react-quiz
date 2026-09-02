# React Quiz

A small React quiz application that loads questions from a local JSON server, tracks the user's progress, calculates points, and keeps a high score during the session.

## Features

- Start screen with the number of questions
- Multiple-choice quiz flow
- Score tracking and progress bar
- Countdown timer for each question
- Finish screen with final score and high score
- Restart quiz flow

## Tech Stack

- React
- JavaScript
- JSON Server
- Create React App

## Project Structure

- `src/components` – UI components for the quiz flow
- `src/index.js` – app entry point
- `src/index.css` – styling
- `data/questions.json` – quiz questions and answers

## Getting Started

1. Install dependencies:

   ```bash
   npm install
   ```

2. Start the JSON server for the quiz data:

   ```bash
   npm run server
   ```

3. Start the React app in a separate terminal:

   ```bash
   npm start
   ```

4. Open the app in your browser at:

   ```text
   http://localhost:3000
   ```

## Available Scripts

- `npm start` – runs the React app
- `npm run server` – runs the local JSON API on port 8000
- `npm run build` – creates a production build
- `npm test` – runs the test suite

## Notes

This app fetches questions from `http://localhost:8000/questions`, so the JSON server must be running before launching the quiz.
