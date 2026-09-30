# VelwavesAS Tier List

A clean static tier-list website designed for Vercel.

## Deploy to Vercel
1. Upload this folder to a GitHub repository.
2. In Vercel, import the repository.
3. Framework preset: **Other** (static site).
4. Build command: leave empty.
5. Output directory: `.`
6. Deploy.

## Add players
Edit `app.js` and put names inside the desired tier, for example:

```js
sword:{HT2:['PlayerOne','PlayerTwo'],LT2:['PlayerThree']}
```

The current version is frontend-only. To make `/result` from your Discord bot automatically update the website, connect `app.js` to a database/API (Supabase, Firebase, or a Vercel API route) and have your bot write results there.
