# Animated Motion Button Demo

This small demo shows an animated "motion" button with decorative geometric
images that reveal and move on hover. The repository contains multiple simple
HTML pages so you can test navigation and different game states.

Pages included:
- `index.html` — main "Play" page with the animated button
- `level1.html` — a sample "Level 1" page
- `gameon.html` — "Game On" page (button advances to Game Over for demo)
- `gameover.html` — "Game Over" page (button returns to Play)

How to run locally
1. Open `index.html` directly in a browser (double-click or use `Start-Process` in PowerShell).
2. Or run a tiny local server from the project folder (recommended):

```powershell
# from the project directory
python -m http.server 8000
# then open http://localhost:8000
```

Customizing the visible text
- The visible words on each page are the `.button__text` contents in the HTML files.
- You can change them to any strings like "play", "level 1", "game on", "game over".

Notes and next steps
- All pages share `style.css` so styling changes apply everywhere.
- If you'd like the buttons to react on click instead of hover (for mobile), I can add
	a small JavaScript file that toggles a class to trigger the same animation.

Credits: Based on a short tutorial / demo for a CSS animated button.