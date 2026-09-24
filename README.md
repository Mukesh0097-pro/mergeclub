# mergeclub — waitlist

single-screen waitlist. mobile-first. one file: `index.html`. no nav, no scroll, no sections.

## run locally

```bash
cd mergeclub
python3 -m http.server 8000
# open http://localhost:8000
```

no build step. google fonts with system fallback offline.

## signups (exportable)

- posts to formspree (`https://formspree.io/f/xjykowzl`). check submissions in the formspree dashboard, export csv there.
- also saves to `localStorage` key `mergeclub_waitlist` as backup.
- email validated, duplicates blocked (case-insensitive).
- after submit the form is replaced with `you're in. we'll email you before the drop.`

## deploy

vercel: import the github repo `Mukesh0097-pro/mergeclub`, deploy. static, no build settings needed.

## brand (strict)

- espresso `#16130E` bg, ivory `#F2EBDD` text/inputs, brass `#C19A5B` accents only.
- space grotesk headline, inter body, jetbrains mono label. all regular weight.
- merge motif (two thin blue lines, hollow ends, solid dot) bottom corner + favicon.
