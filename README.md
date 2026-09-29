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
- `src/data/questions.json` – quiz questions and answers

## Getting Started

1. Install dependencies:

   ```bash
   npm install
   ```

2. Start the React app:

   ```bash
   npm start
   ```

3. Open the app in your browser at:

   ```text
   http://localhost:3000
   ```

## Available Scripts

- `npm start` – runs the React app
- `npm run server` – optionally runs the local JSON API on port 8000
- `npm run build` – creates a production build
- `npm test` – runs the test suite

## Deployment

The quiz data is bundled with the React app, so no separate API server is needed in production. Deploy to a static hosting provider such as Netlify or Vercel with:

- Build command: `npm run build`
- Publish/output directory: `build`
