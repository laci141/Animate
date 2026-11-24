# Animate

**Live: https://rootwatch.pages.dev/**

Animate is a small collection of living simulations that you can watch grow and respond in real time. It is plain HTML, CSS and JavaScript with no build step.

## Simulations

- **Rootwatch** — a seedling through dawn, noon, dusk and moonlight, above and below the soil. Change sunlight, water and nutrients, speed up time, make it rain, or reset and start over. Live: https://rootwatch.pages.dev/rootwatch

## Run locally

Open the folder in a terminal and start any static file server, for example:

```bash
python -m http.server 8000
```

Then open http://localhost:8000/.

## Notes

- The hub page has a light/dark theme toggle.
- Both pages respect `prefers-reduced-motion` (no continuous animation, one static frame).
- Deployed from `main` with Cloudflare Pages.
- See `LICENSE` for the license.
