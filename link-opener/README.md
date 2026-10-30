# Multiple Link Opener

A simple single-page tool: paste links (one per line) and open them all in new tabs at once.

## How to use

1. Open `index.html` in a browser (or via GitHub Pages).
2. Paste links into the text box, one per line. `https://` is added automatically if missing.
3. Click **Open All Links**. Each link opens in a new tab, 400ms apart.
4. Your list is saved in the browser (localStorage), so it is still there when you come back.

## Features

- Live count of valid links (invalid lines are skipped)
- Duplicate links removed automatically
- Click any link in the list to open it alone, or remove it
- Copy List and Clear buttons
- No server, no tracking, no dependencies — one HTML file

## Note

Browsers may block multiple tabs as pop-ups. If only one tab opens, allow pop-ups for the page and try again.
