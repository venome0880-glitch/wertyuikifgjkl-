# Shafed Billi – Website

Static multi-page site (no build step, no dependencies).

## Pages
index.html (Home) · features.html · commands.html · sources.html · invite.html · support.html · rules.html

## Run locally
Open `index.html` in a browser, or serve the folder: `npx serve .` or `python -m http.server 8080`.

## Before going live – edit `assets/js/app.js` (top of file)
```js
const CONFIG={clientId:"YOUR_CLIENT_ID",supportUrl:"",repo:"..."};
```
- `clientId`: your bot's Discord Application ID (enables the Invite button)
- `supportUrl`: your Discord support server invite

## Deploy
Drag the folder onto Vercel, Netlify or Cloudflare Pages, or push it to GitHub Pages. `index.html` is the entry point.

## Credits
Bot: Shafed Billi by DEVROCK (see the bot's LICENSE.md). Website: VENOME.
