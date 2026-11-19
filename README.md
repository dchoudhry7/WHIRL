# WHIRL

Website for WHIRL Chocolate Swirl, an ultra-filtered protein shake.

The hero is a short film that plays once when the page opens: 241 full-HD frames (121 rendered frames plus 120 AI in-between frames made with RIFE) drawn one at a time to a canvas at 48 fps, about five seconds, opening on a sharp 4K still and freezing on its own last frame. The film sits in its own block beside the headline, showing a 4:3 window of each frame centred on the bottle, and is never drawn larger than the frames' real pixels, so it stays sharp. A gym section shows the bottle on a dumbbell. Below that: the numbers, a comparison table, the ritual, a hold-to-shake interaction, FAQ and an order form.

Plain HTML, CSS and JavaScript. No build step.

## Run locally

```
python -m http.server 8080
```

Then open http://localhost:8080. Opening `index.html` directly also works, but a local server is the true preview.

## Structure

- `index.html`: the whole site (markup, styles, scripts)
- `assets/f1080/`, `assets/f720/`: film frames (full HD for laptops and desktops, 720p for small windows)
- `assets/hero-start-*.webp`: 4K-class opening still
- `assets/hero-m-*.webp`: the phone hero (phones get a still image instead of the animation)
- `assets/gym-*.webp`: the dumbbell shot
- `assets/*.webp`: section images

## Still to do

- Prices are placeholders.
- The order form shows a thank-you state but is not connected to a store or email service yet.
