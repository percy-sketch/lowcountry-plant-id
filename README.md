# LowCountry Plant ID

A phone app (Progressive Web App) for learning the plants around Pawleys Island, SC, with flashcards, a photo quiz, and a library of every plant photographed.

**Open it:** https://percy-sketch.github.io/lowcountry-plant-id/

## Adding a plant

1. Put a photo in `photos/` (named like `common-name.jpg`, about 1000px on the long side).
2. Add an entry to `plants.json` with the same fields as the existing plants.
3. Commit. GitHub Pages republishes in a minute or two, and the app picks up the new plant on its next open.

## Files

- `index.html`: the whole app (flashcards, quiz, library)
- `plants.json`: plant data
- `photos/`: plant photos
- `sw.js`, `manifest.json`, `icons/`: home-screen install and offline support

Progress (which plants you've learned) is saved on your phone only.
