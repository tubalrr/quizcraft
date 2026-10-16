# QuizCraft

**Play. Learn. Level up.** QuizCraft is a responsive browser-based quiz platform built with plain HTML, CSS, and JavaScript.

## Features
- Built-in quiz categories: General, Science, Technology, Geography, and Gaming
- Mixed, Easy, Medium, and Hard difficulty filters
- Quick (5), Classic (10), and Marathon (15) rounds
- Optional countdown timer
- Immediate answer feedback and explanations
- Scores, round results, and saved play statistics
- Daily Challenge: a deterministic mixed-topic set that changes by local calendar date
- Achievement shelf with milestones for quiz completion, perfect rounds, topic exploration, quiz creation, and daily play streaks
- Local leaderboard with recent results and editable player name
- Custom quiz creator with four multiple-choice answers per question
- Import and export individual custom quizzes or a full JSON backup
- Responsive layout for desktop and mobile
- No external libraries, build step, backend, or API key required

## Run locally
Open `index.html` in a modern browser.

## Publish with GitHub Pages
This repository includes a GitHub Actions workflow at `.github/workflows/deploy.yml`. It deploys the repository root whenever code is pushed to `main`. Configure **Settings → Pages → Build and deployment → Source: GitHub Actions** if Pages isn't already configured.

## Data and privacy
Quiz sets, player name, play history, and stats are stored in the browser's `localStorage`. They are not synchronized between devices and can be lost if browser storage is cleared. The leaderboard is local to the browser; it is not an online/global leaderboard. No account system or backend is included yet.

Use **My quizzes → Export all** to download a JSON backup. Import a QuizCraft JSON backup or a single quiz JSON file to restore/share custom sets.

## Project files
- `index.html` — the single-file app, styles, built-in question bank, and application logic
- `.github/workflows/deploy.yml` — automatic GitHub Pages deployment

## Status
A client-side starter platform. Custom questions and scores remain on the user's device.
