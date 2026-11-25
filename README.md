# Aurum – Trading Journal

Personal trading journal (single-page web app, installable on a phone). All data stays in your own browser (localStorage); nothing is sent to any server.

## Files
- `index.html` – the whole app
- `manifest.webmanifest`, `icon-*.png` – install-to-home-screen support
- `sw.js` – offline cache (change `VERSION` inside it when you publish a new `index.html`)

## Publish on GitHub Pages
1. Create a repository and upload all files in this folder to the root.
2. Settings → Pages → Source: *Deploy from a branch* → Branch: `main`, folder `/ (root)` → Save.
3. Open `https://<your-username>.github.io/<repo-name>/`.

## Moving your data
Browser data is tied to the address, so the new GitHub address starts empty.
Before switching: open the old copy → Backup → **Backup (JSON)**.
On the new address: Backup → **Choose backup file**.
