# Buffer — a time-adaptive airport navigation experience

Design case study for **Buffer**, an airport wayfinding concept whose interface compresses as the time left before boarding shrinks.

**Interactive prototype:** https://buffer-prototype.lovable.app

## What's inside

- `index.html`: the whole case study (layout, copy, styles and scroll animations) in one file.
- `screens/`: app screenshots for the four time states (Comfortable, Constrained, Tight, Critical).

## The four time states

| State | Buffer | Interface |
|---|---|---|
| Comfortable | 40+ min | Full map, nearby places, browsing is safe |
| Constrained | 25–40 min | Next step leads; only stops on the way |
| Tight | 10–25 min | Route and live countdown only |
| Critical | under 10 min | One instruction, full screen |

## Run locally

It's a static page with no build step. Open `index.html`, or serve the folder:

```bash
python3 -m http.server 8000
```

Animations use [GSAP](https://gsap.com) and ScrollTrigger from cdnjs; fonts load from Google Fonts. Both need an internet connection.
