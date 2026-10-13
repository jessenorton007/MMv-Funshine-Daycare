# Funshine website

This imported project is a static HTML, CSS, and JavaScript website. Preserve its existing structure and stack.

## Running on Replit

Use the **Start application** workflow (the Run button). It runs `PORT=5000 npm start`, serving the site on `0.0.0.0:5000` in Preview.

No package dependencies, secrets, database, or external services are required. Node.js 18 or newer is sufficient. For a local preview outside Replit, `npm start` uses port 4173 by default.

## Checks

- `npm run check` checks the browser JavaScript syntax.
- `node --check server.mjs` checks the preview server syntax.

## Existing behavior

The tour inquiry form opens the visitor's email app and offers a copyable inquiry; it does not submit or store messages on a server. The website remains a design preview with `noindex,nofollow`. Confirm business details with the center before a public launch.
