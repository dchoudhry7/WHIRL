# WHIRL

Website for WHIRL Chocolate Swirl, an ultra-filtered protein shake.

The hero is a single product photo, AI-upscaled 4x and served in several sizes (1280 to 3840 px wide), so every screen gets an image at least as large as it displays and it never looks pixelated. Below it is the full site: the numbers, a comparison table, the ritual, a hold-to-shake interaction, FAQ and an order form.

Plain HTML, CSS and JavaScript. No build step.

## Run locally

```
python -m http.server 8080
```

Then open http://localhost:8080. Opening `index.html` directly also works, but a local server is the true preview.

## Structure

- `index.html`: the whole site (markup, styles, scripts)
- `assets/hero-ice-*.webp`: the hero photo in 1280, 1920, 2560 and 3840 px widths
- `assets/hero-ice-m-*.webp`: a portrait crop of the hero for phones
- `assets/*.webp`: section images

## Still to do

- Prices are placeholders.
- The order form shows a thank-you state but is not connected to a store or email service yet.
