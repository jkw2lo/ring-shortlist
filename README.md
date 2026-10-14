# Ring Shortlist

A small page for narrowing down an engagement ring. Cross off the features you don't want, mark the ones you love, and log every ring you try on with a photo, notes and a yes / maybe / no verdict. A summary panel shows what's left and copies a set of notes to send a jeweler.

Live version: https://claude.ai/artifact/KjXQbYB3MXxLMkSanBJq9Q

## How it saves

`ring-shortlist.html` is published as a Claude artifact. There it saves marks and try-ons to the owner's private data in the artifact's database, and photos to its asset store. Opened anywhere else, it falls back to `localStorage` in that browser, and photo uploads are hidden.

The file is written for the artifact host, which wraps it in the `<!doctype html>`, `<head>` and `<body>` tags, so it has none of its own.
