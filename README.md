# Love You ❤️

A multilingual heart animation made from “I love you” in 20 languages.

## Open the website

After the **Deploy Love You website to GitHub Pages** workflow finishes successfully, visit:

**https://buxl0y.github.io/loveYou/**

The website version is plain HTML, CSS, and JavaScript, so it runs in a browser on desktop and mobile without installing Python or other dependencies.

## Run locally

Open `index.html` in your browser, or start a simple local server from the repository folder:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

## Desktop Python version

The original `love.py` desktop animation is preserved. It uses Python's standard library (`turtle` and `tkinter`) and can be run with:

```bash
python love.py
```

## Deployment

The GitHub Actions workflow in `.github/workflows/pages.yml` deploys the static website to GitHub Pages whenever `index.html`, the workflow, or this README changes on `main`. If Pages is not enabled in repository settings, enable it and select **GitHub Actions** as the build and deployment source.
