# tadco.co.id

Baseline source repository for the public TADCO website.

## Status

This first version is a **reconstruction generated with Hostinger Agent**, not a native export from Hostinger AI Builder. It now uses approved local copies of the public TADCO logo and photography while spacing, animations, remaining sections, and responsive details are still being matched to the live site.

## Run locally

```bash
python3 -m http.server 4174
```

Then open `http://127.0.0.1:4174`.

## Known gaps

- The desktop homepage reference currently covers the hero, services, and the beginning of About; the remaining page still needs visual comparison.
- A mobile reference has not yet been captured, so responsive fidelity remains unverified.
- No contact-form submission backend is included.

## Repository layout

- `index.html` — one-page public website
- `styles.css` — responsive styling
- `images/` — approved visual assets to be added during visual-matching work
