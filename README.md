# Grainhold

A small fog-of-war settlement builder. Pure HTML/CSS/JS — no build step, no dependencies.

## How to play
- Click a glowing fogged tile next to your land to **scout** it (3 gold, uses 1 of your 3 daily actions).
- Click a scouted tile touching land you own to **claim** it (gold cost varies by terrain, also uses 1 action).
- Claimed plots don't yield anything right away — they take 2 to 5 days to mature depending on terrain
  (plains are fastest, wasteland slowest). Click **End Day** to advance growth.
- Once a plot shows a gold ring and "Ready to harvest!", select it and click **Harvest** to collect its bread.
- Your homestead itself produces a small trickle of bread automatically every day, no clicking needed.
- Sell bread at the Caravan Post for gold.
- You only get 3 scout/claim actions per day, so expansion is deliberately slow — plan which tiles matter.
- Progress autosaves to your browser's local storage, per connected address.

## Deploy on Vercel via GitHub

1. Create a new GitHub repo and push these files (`index.html`, `vercel.json`, `README.md`) to it.
2. Go to https://vercel.com/new, import that repo.
3. Framework preset: **Other** (or "Static"). No build command, no install command needed —
   Vercel will just serve `index.html` as-is.
4. Deploy. Done.

You can also use GitHub Pages instead: enable Pages in the repo settings, point it at the
root of the `main` branch, and it will serve `index.html` directly — no config needed there either.
