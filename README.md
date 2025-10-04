# Aruzz Fashion — Static Site (Tailwind CDN)

This is a ready-to-run static website for **Aruzz Fashion** using Tailwind via CDN.

## Run locally (VS Code)
1. Open this folder in VS Code.
2. Install the recommended extensions when prompted (Live Server + Prettier).
3. Right-click `index.html` → **Open with Live Server** (or click the "Go Live" button).
4. Your site will open at http://127.0.0.1:5500 (or similar).

## Structure
```
aruzz-fashion-site/
├─ index.html
├─ assets/
│  ├─ css/custom.css
│  ├─ js/main.js
│  └─ img/            # put your images here
└─ .vscode/           # editor settings & extension recommendations
```

## Notes
- Tailwind is loaded via CDN in `index.html` — no build step needed.
- Add custom scripts in `assets/js/main.js` and styles in `assets/css/custom.css`.
- Replace Unsplash image URLs with your own product photos in `index.html`.
