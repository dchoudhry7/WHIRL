# WHIRL

Website for WHIRL Chocolate Swirl, an ultra-filtered protein shake.

The design is called the pour. The hero is one full-width splash photo of the bottle (AI-upscaled to 4K, served at the size each screen needs), with the headline nested inside the splash ring. The photo's bottom edge pours into a chocolate section, and from there milk and chocolate sections take turns, each change marked by a slowly moving liquid surface.

Plain HTML, CSS and JavaScript. No build step.

## Run locally

```
python -m http.server 8080
```

Then open http://localhost:8080. Opening `index.html` directly also works, but a local server is the true preview.

## Structure

- `index.html`: the whole site (markup, styles, scripts)
- `assets/hero-splash-*.webp`: the hero photo (1400 to 4000 wide, transparent background)
- `assets/hero-splash-m-*.webp`: the phone crop of the hero photo
- `assets/gym-*.webp`: the dumbbell shot
- `assets/*.webp`: section images

## Still to do

- Prices are placeholders.
- The order form shows a thank-you state but is not connected to a store or email service yet.
