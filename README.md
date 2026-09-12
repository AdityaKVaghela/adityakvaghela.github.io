# Aditya Vaghela — iOS Portfolio

Personal portfolio site. Live at **https://adityakvaghela.github.io**

Senior iOS engineer — Swift, SwiftUI, UIKit, Objective-C, Flutter.

## Stack

Static HTML. No build step, no dependencies, no framework.

```
index.html         the whole site — markup, CSS and one inline script
assets/apps/*.jpg  two screens per app
```

- **Type** — Syne (display), Manrope (body), JetBrains Mono (data), via Google Fonts
- **Design** — single dark theme, every colour painted explicitly
- **Animation** — hero entrance, scroll reveals, count-up stats, pointer tilt on the
  app shots, drifting aurora, marquee, scroll progress, nav section-spy.
  All of it disabled under `prefers-reduced-motion: reduce`
- **Accessibility** — reveal states are applied by JavaScript only, so the page renders
  fully visible with JS off; visible focus rings; alt text on every image
- **Performance** — ~133KB to first paint; the rest of the images lazy-load

## Run locally

```bash
python3 -m http.server 8791
```

Then open http://localhost:8791

## Deploy

Pushing to `main` publishes to GitHub Pages automatically.

```bash
git add -A && git commit -m "Update portfolio" && git push
```

## Contact

- Email — adityavk.work@gmail.com
- LinkedIn — https://linkedin.com/in/adityakvaghela
- Upwork — https://www.upwork.com/freelancers/~013424d2845294ff40
