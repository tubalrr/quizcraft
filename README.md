# QuizCraft

**Play. Learn. Level up.** QuizCraft is a responsive browser-based quiz platform built with plain HTML, CSS, and JavaScript.

## Features
- Five built-in categories: General, Science, Technology, Geography, and Gaming
- Mixed, Easy, Medium, and Hard difficulty filters
- Quick (5), Classic (10), and Marathon (15) round settings
- Optional per-question countdown timer
- Immediate answer feedback and explanations
- Scoring, round results, and saved stats
- Custom quiz builder with four answer choices per question
- Save, play, and delete your own quiz sets
- Responsive layout for desktop and mobile
- No dependencies, build step, server, account, or API key required

## Run locally
Open `index.html` in a modern browser.

## Publish with GitHub Pages
1. Open the repository's **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/(root)`, then save.
4. Wait for GitHub Pages to finish publishing, then open the Pages URL shown in Settings.

If GitHub does not offer Pages for this private repository on the current plan, make the repository public or use a hosting option that supports private repositories.

## Data and privacy
QuizCraft stores custom quiz sets and player stats in the browser's `localStorage`. This data stays in that browser profile on that device; it is not synced between devices and may be lost if browser storage is cleared. There is no backend or online leaderboard yet.

## Project files
- `index.html` — the entire app, styles, built-in question bank, and JavaScript

## Status
Starter version. The app works without external libraries. Custom quizzes and progress are local to each browser.
