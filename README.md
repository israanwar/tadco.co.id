# tadco.co.id

Baseline source repository for the public TADCO website.

## Status

This first version is a **reconstruction generated with Hostinger Agent**, not a native export from Hostinger AI Builder. It preserves the initial information architecture and copy while the original visual assets, spacing, typography, animations, and responsive details are still being matched to the live site.

## Run locally

```bash
python3 -m http.server 4174
```

Then open `http://127.0.0.1:4174`.

## Known gaps

- `images/logo.png` and `images/hero.jpg` still need to be supplied from approved TADCO assets.
- Several image areas remain intentional placeholders.
- The Blog navigation target is not implemented yet.
- No contact-form submission backend is included.

## Repository layout

- `index.html` — one-page public website
- `styles.css` — responsive styling
- `images/` — approved visual assets to be added during visual-matching work
