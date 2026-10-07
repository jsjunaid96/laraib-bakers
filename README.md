# Laraib Bakers & Sweets — Website

Trial website for **Laraib Bakers & Sweets, 8-km Multan Road, Lahore**.
Static site: no database, no backend. Cart is stored in the visitor's browser (localStorage) and checkout opens a pre-filled WhatsApp order to 0324-1111663.

## Files
- `index.html` — page structure and content (all 28 products are written into the HTML)
- `style.css` — all styling (Laraib green brand system)
- `script.js` — category filters, cart, product popup, checkout

## Run locally
Open the folder in VS Code and use Live Server ("Go Live" on `index.html`), or open `index.html` in a browser.

## Go live (free)
GitHub Pages: repo **Settings → Pages → Deploy from branch → main / root**. Your site gets a public link.
Netlify/Vercel also work: drag-and-drop this folder or connect the repo.

## Prices note
Only 4 items carry the bakery's published shop prices (Gulab Jamun Rs 1,090 · Laddu Rs 1,500 · Dill Barfi Rs 1,700 · Kit Kat Cake Rs 1,990). All other prices are demo prices for the trial — replace them with the client's confirmed price list before launch.

## Editing workflow
Code lives in this repo. To change anything (prices, items, photos, hours), edit the files here or ask Muse to prepare the updated files, then commit/push — GitHub Pages redeploys automatically.
