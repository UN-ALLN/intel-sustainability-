# Changes Summary

## style.css (was empty — fully written)

| Area | What changed |
|---|---|
| **Body** | Dark navy background (`#0f1923`), `Segoe UI` font |
| **Hero / Header** | Blue gradient (`#003c71` → `#0068b5` → `#00aeef`), centered flex column, Intel logo white-filtered to 140px, h1 fluid size with text-shadow, subheading in light blue |
| **Timeline section** | `display: flex; flex-direction: row; overflow-x: auto` — horizontal scroll on large screens |
| **Scroll Snap (extra credit)** | `scroll-snap-type: x mandatory` on `<section>`, `scroll-snap-align: start` on each card |
| **Cards** | Dark card background (`#152535`), rounded corners, blue accent border on hover |
| **Card hover — CSS Transforms (extra credit)** | `translateY(-8px) scale(1.02)` lift + blue glow shadow; image zooms `scale(1.06)` |
| **Card hover — detail reveal** | `<p>` text hidden (`max-height: 0; opacity: 0`) by default; animates open on hover |
| **Responsive (≤640px)** | `flex-direction: column`, scroll-snap off, cards full-width, hover transforms disabled, text always visible |

## index.html (starter code updated)

| Area | What changed |
|---|---|
| **Scroll hint** | Moved above `<section>` so it appears between hero and timeline |
| **Cards 1–4** | Added `<img>` tags using the existing `img/1.jpg`–`img/4.jpg` placeholder images |
| **Cards 5–9** | Added `<img>` tags using Unsplash stock photos (emissions, wind turbines, green earth, solar panels, summit meeting) — Custom Images extra credit |

## Extra Credit Completed

- **Scroll Snap (5 pts)** — `scroll-snap-type` / `scroll-snap-align` in CSS
- **CSS Transforms (5 pts)** — `translateY` + `scale` on card hover, `scale` on card image hover
- **Custom Images (5 pts)** — Cards 5–9 use thematically matched stock photos via Unsplash
