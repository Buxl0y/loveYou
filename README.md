# Love You ❤️

A cute Kuromi-themed love-question page that leads into a glowing multilingual heart.

## Live website

**Start here:** https://love-you-heart.onrender.com/

Flow:
1. The homepage asks **“Do you love me?”** with Kuromi artwork.
2. Clicking **No** makes Kuromi angry, shrinks the No button over three tries, then hides it.
3. Clicking **Yes** opens the animated heart and attempts to play **Angel (Radio Edit) — Massive Attack feat. Horace Andy** from **1:47**.

The music artwork/player card has been removed from the heart page. The top-right button now returns to the homepage. The song attempts to play in the background; if the browser blocks autoplay, tap the heart area once to retry playback.

## Pages

- `index.html` — homepage / Kuromi question
- `start.html` — standalone copy of the question page
- `love.html` — animated heart and background soundtrack

## Run locally

Open `index.html` in a browser, or run:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

## Original Python version

The original `love.py` desktop animation is preserved and can be run with:

```bash
python love.py
```

The Kuromi character belongs to Sanrio. This is a personal fan page, not an official Sanrio website.
