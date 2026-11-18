# WHIRL

Website for WHIRL Chocolate Swirl, an ultra-filtered protein shake.

The hero is a scroll-driven animation: 190 HD frames drawn to a canvas, with each step blended between the two nearest frames so scrolling stays smooth. Below it is the full site: the numbers, a comparison table, the ritual, a hold-to-shake interaction, FAQ and an order form.

Plain HTML, CSS and JavaScript. No build step.

## Run locally

```
python -m http.server 8080
```

Then open http://localhost:8080. Opening `index.html` directly also works, but a local server is the true preview.

## Structure

- `index.html`: the whole site (markup, styles, scripts)
- `assets/frames-1080/`: 1920×1080 scroll frames for laptops and desktops
- `assets/frames-720/`: 1280×720 scroll frames for smaller screens
- `assets/*.webp`: section images and the phone hero

Phones and reduced-motion visitors get a still hero image instead of the frame sequence.

## Still to do

- Prices are placeholders.
- The order form shows a thank-you state but is not connected to a store or email service yet.
