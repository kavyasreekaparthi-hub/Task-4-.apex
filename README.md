# Responsive Interactive Web Demo

## Objective
Gain advanced skills in CSS and JavaScript by building a responsive, interactive webpage that includes:
- Responsive design via media queries
- Image carousel
- Interactive quiz
- Live data fetched from public APIs (joke + weather)

## Features

1. **Responsive Design**
   - Fluid typography and layout that adapts to mobile, tablet, and desktop using CSS media queries and flexible grid.
   - Cards, buttons, and components resize and stack appropriately on small screens.

2. **Image Carousel**
   - Auto-rotates images every few seconds.
   - Manual navigation with previous/next controls.
   - Indicator dots for current slide.
   - Pause/resume auto-rotation.
   - Basic swipe support for touch devices.

3. **Interactive Quiz**
   - Multiple questions with immediate feedback.
   - Highlights correct/incorrect answers.
   - Score tracking.
   - Accessible via keyboard (Enter/Space to select).

4. **API Integration**
   - **Joke API:** Fetches a random joke from `icanhazdadjoke.com` (no API key needed).
   - **Weather API:** Fetches current weather from Open-Meteo based on latitude and longitude (no API key required). User can change coordinates.

## Usage

1. Save the provided HTML as `index.html`.
2. Commit and push to a GitHub repository.
3. (Optional) Enable GitHub Pages on the repository to serve it as a static site.
4. Open in a browser — it works offline except for the live API sections (needs internet for jokes/weather).

## Customization

- Replace carousel image URLs with your own images.
- Extend the quiz by editing the `quizData` array in the JavaScript.
- Change default coordinates in the weather widget to your location.
- Add more APIs by following the existing `fetch` patterns.

## Deployment

Example Git commands:

```bash
git init
git add index.html README.md
git commit -m "Initial responsive interactive demo"
git branch -M main
git remote add origin <your-github-repo-url>
git push -u origin main
