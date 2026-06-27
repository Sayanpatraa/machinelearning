# The Art of Modelling

A static course website for first-principles machine learning lessons by Sayan Patra.

## Pages

- `index.html`: homepage with course introduction, roadmap, about section, and motive.
- `courses.html`: course library.
- `lessons/simple-linear-regression.html`: Week 1 lesson page.
- `assets/style.css`: course-style off-white warm, minimal design system.
- `assets/script.js`: mobile navigation, reading progress bar, and active lesson sidebar.

## How to run locally

Open `index.html` directly in your browser.

For a cleaner local server, run one of these from the repo folder:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## How to deploy

Good beginner-friendly options:

- GitHub Pages
- Netlify
- Vercel

Since this is a static website, no backend is required.

## Design direction

The website uses a warm, reading-first style:

- off-white background
- soft cards
- brown/orange accent
- sticky navigation
- lesson sidebar
- responsive layout
- minimal JavaScript

## Next improvements

- Add MathJax or KaTeX for better equations.
- Add diagrams for OLS, residuals, and gradient descent.
- Add Python code examples.
- Add quizzes and checkpoints.
- Add more weekly modules.
