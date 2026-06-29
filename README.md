# O.C.E.A.N Case Manager Demo

A lightweight single-page demo app for case management workflows focused on Regulation E and related dispute handling.

## What it includes

- `index.html` — the main demo application UI.
- `style.css` — app styling extracted from the inline HTML.
- `script.js` — core JavaScript logic for case creation, review, ledger, manager review, and audit workflows.

## Features

- Case intake and creation
- Investigator review dashboard
- Audit-ready case logging
- Ledger and recovery workflow views
- Import/export case data as JSON

## Run locally

1. Open `index.html` in a browser.
2. Or serve the folder using a static file server:
   - `python3 -m http.server 8000`
   - then open `http://localhost:8000`

## Notes

- This is a demo/prototype app; data is stored in browser local storage.
- `MANAGER123` is used in the demo for manager override prompts.
