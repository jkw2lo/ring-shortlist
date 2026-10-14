# Ring Shortlist

A small page for narrowing down an engagement ring, written for someone who doesn't know the vocabulary yet.

- **This or that:** compares two options at a time and crosses off the one you don't pick, category by category, until one ring is left.
- **On my hand:** upload a photo of your hand, mark the edges of your ring finger, and rings are drawn on it to scale for your ring size. Compare every carat size, shape, setting or metal on your own finger.
- **All options:** every option (shape, setting, prongs, band, width, metal, stone, carat, height, wedding band fit) is drawn to scale for your ring size, from above and from the side. Cross off what you don't want and mark what you love.
- **Style quiz:** seven picture-based questions that suggest loves and cross-offs to add to your board.
- **Mix & match:** draws every combination of what's still on your shortlist, so you can save the designs you like.
- **Try-ons:** log rings you tried with a photo, notes and a yes / maybe / no verdict, then turn a yes or no into loves or cross-offs on your board.
- **Share my picks:** a one-page image of your best guess, saved designs, loves and ring size for a partner or jeweler.

A summary panel draws your best-guess ring and copies a set of notes to send a jeweler. The drawings are generated in the page as SVG, with no image files.

Live version: https://claude.ai/artifact/KjXQbYB3MXxLMkSanBJq9Q

Also on GitHub Pages: https://jkw2lo.github.io/ring-shortlist/ (`index.html` just forwards to `ring-shortlist.html`).

## How it saves

`ring-shortlist.html` is published as a Claude artifact. There it saves marks and try-ons to the owner's private data in the artifact's database, and photos to its asset store. Opened anywhere else, it falls back to `localStorage` in that browser, and photo uploads are hidden.

The file is written for the artifact host, which wraps it in the `<!doctype html>`, `<head>` and `<body>` tags, so it has none of its own.
