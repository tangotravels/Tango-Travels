# Tango Travels

A personal travel journal site. Static HTML/CSS/JS — no build step, no dependencies, no backend.

## Structure
```
index.html              → landing page (list of trips)
vietnam/index.html       → Vietnam itinerary, day by day
vietnam/images/          → photos & video clips for the Vietnam trip
```

## Running locally
Just open `index.html` in a browser. To add more trips, create a new folder (e.g. `japan/`) with its own `index.html` + `images/`, and add a card for it on the landing page.

## Hosting for free (recommended: GitHub Pages)
1. Create a free GitHub account at github.com if you don't have one.
2. Create a new repository (e.g. `tango-travels`), and upload this whole folder to it (drag-and-drop works on github.com, or use `git push` if you're comfortable with git).
3. In the repo, go to Settings → Pages → set "Source" to the main branch, root folder.
4. GitHub will give you a live URL like `https://yourname.github.io/tango-travels/` within a minute or two.
5. Share that link with anyone — it works on any device, no login needed.

Updating later: just upload the new/changed files (or `git push`), and the live site updates automatically within a minute.
