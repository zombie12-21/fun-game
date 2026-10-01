# ARMORY // Illustrated Gun Bestiary

A static illustrated catalog of 103 iconic firearms — searchable bestiary, loot-crate opener with rarity odds, and a persistent collection vault (localStorage). No build step, no dependencies, works from any static host.

## Put it on GitHub Pages (free, ~2 minutes)

1. Create a new repo at github.com (e.g. `armory`) — do NOT check "Add a README".
2. Click **Add file → Upload files**, drag in `index.html`, then **Commit changes**.
3. Go to **Settings → Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, Branch to **main** + **/(root)**, then **Save**.
4. Wait ~1 minute. Your site is live at `https://YOUR-USERNAME.github.io/armory/`.

## Run locally

Just double-click `index.html`, or serve it:

```
npx serve .
```

## Notes

- Your loot collection is stored per-browser in `localStorage` under the key `armoryLootV1`.
- Everything (data, art, logic) lives in the single `index.html` file.
