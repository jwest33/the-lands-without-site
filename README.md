# The Lands Without - Website

Marketing site for The Lands Without, an isometric dark fantasy MMORPG. Static HTML/CSS/JS served by GitHub Pages at [thelandswithout.com](https://thelandswithout.com).

## Local preview

```bash
python -m http.server 8090
# open http://localhost:8090
```

## Structure

- `index.html` - single-page landing
- `css/style.css` - theme ported from the in-game UI (silver/black palette, panel frames, bevels)
- `js/main.js` - scroll reveal and mobile nav, no dependencies
- `assets/` - fonts and images copied from the game repo
- `CNAME` - custom domain for GitHub Pages

## Adding screenshots

Drop PNG/JPG files into `assets/img/screenshots/` and replace the placeholder frames in the gallery section of `index.html`.
