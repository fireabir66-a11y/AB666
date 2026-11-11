# AB666 — Play-credit website prototype

## Files
- `index.html` — page structure
- `style.css` — responsive teal/gold interface
- `app.js` — navigation, game simulations, local profile/history and demo admin tools

## Run locally
Open `index.html` in a modern browser.

## Publish with GitHub Pages
1. Open your `AB666` GitHub repository.
2. Upload `index.html`, `style.css`, and `app.js` to the repository root (not inside another folder).
3. Commit the changes.
4. In Settings → Pages, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
5. Wait for GitHub Pages to publish, then refresh your site.

## Demo admin
Open Admin from the bottom navigation or side menu. Demo PIN: `666666`.

## Important limitations
This is a front-end prototype. Credits and history are stored only in the current browser using localStorage. It has no real user accounts, server, Supabase connection, real payment processing, cash withdrawals, or secure admin authentication. The demo PIN is visible in the JavaScript and is not security. Do not use it to handle real money or personal financial information. Game outcomes are simulated and are not secretly adjustable.
