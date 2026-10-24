# Love You ❤️

A cute Kuromi-themed love-question page that leads into a glowing multilingual heart.

## Live website

**Start here:** https://love-you-heart.onrender.com/

Flow:
1. The homepage asks **“Do you love me?”** with Kuromi artwork.
2. Clicking **No** changes Kuromi to an angry mood, shrinks the button over three tries, then hides it.
3. Clicking **Yes** opens the existing Love You animation and attempts to play **Angel (Radio Edit) — Massive Attack feat. Horace Andy** from **1:47**.

The browser may block autoplay. If that happens, click the on-page **Start song from 1:47** button.

## Pages

- `index.html` — homepage / Kuromi question
- `start.html` — standalone copy of the question page
- `love.html` — original animated heart with the YouTube player

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
