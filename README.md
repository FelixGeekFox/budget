# Budget

A small, self-contained budgeting app in a single HTML file. Track your bills
and income with their dates, set aside savings each fortnight, and see a running
read on your account balance plus a preview of what's coming up.

**Live:** _add your GitHub Pages URL here once it's published_

## Features

- **Balance** you can tap to edit (in AUD)
- **Income & bills** with a cadence (weekly / fortnightly / monthly / one-off) and a next-due date
- **Savings per fortnight** — money set aside automatically in the projection
- **Running commentary** that flags the tightest point in the next month
- **Upcoming timeline** showing the balance left after each payment
- **Light & dark** themes
- Everything is saved locally in your browser (`localStorage`) — no account, no server, nothing leaves your device

## Running it

It's one file with no build step and no dependencies. Open `index.html` in any
browser, or host it anywhere that serves static files.

## Hosting on GitHub Pages

1. Push this repo to GitHub.
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*,
   pick the `main` branch and the `/ (root)` folder, and save.
4. After a minute it'll be live at `https://<your-username>.github.io/<repo-name>/`.

On a phone, open that URL and use **Add to Home Screen** for an app-like icon.
