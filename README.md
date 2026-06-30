# Baaeed

Baaeed is a Japanese diet record PWA for tracking weight, meals, steps, body logs, behavior notes, and weekly reviews.

## Public App

This repository is configured for GitHub Pages.

Expected URL:

```text
https://effore4001-spec.github.io/baaeed-app/
```

## Data Storage

User records are stored only in each browser's `localStorage`.

- The app does not collect user records on a server.
- Records are not shared between users.
- Records do not automatically sync across devices or browsers.
- Use the built-in JSON backup and restore features before changing devices or clearing browser data.

## Update Notes

When app files change, update the `CACHE_NAME` in `sw.js` so installed PWAs refresh their cached app shell reliably.
