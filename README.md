# Junxiao Lin — Personal Homepage

Personal academic website: <https://junxiaolin.github.io/>.

This repository contains the static files for the public homepage and CV.
No build step, dependencies, analytics, or external fonts are required.

## GitHub Pages

Under **Settings → Pages**, select **Deploy from a branch**, branch **main**,
and folder **/ (root)**. GitHub Pages serves the committed files directly.

## Local preview

```sh
python3 -m http.server 8001 --bind 127.0.0.1
```

Open <http://localhost:8001/>. The CV is at `/cv.html`.

See [CREDITS.md](CREDITS.md) for image sources.
