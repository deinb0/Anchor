# Anchor — install as a phone app

## 1. Get it on the web (GitHub Pages, same as The Crate)
1. Go to github.com → New repository → name it `anchor` (public).
2. Upload all files in this folder (`index.html`, `manifest.json`, `service-worker.js`, `icons/`) keeping the folder structure.
3. Repo → Settings → Pages → Source: "Deploy from a branch" → Branch: `main` / `root` → Save.
4. Wait ~1 minute, then your app is live at `https://<your-username>.github.io/anchor/`.

## 2. Install it on your phone (Android / Chrome)
1. Open that URL in Chrome on your phone.
2. Tap the ⋮ menu → "Add to Home screen" (or Chrome may prompt you automatically).
3. Confirm — you'll get a real app icon that opens full-screen, no browser bar.

## 3. Turn on AI-powered chat filing (free, via Google AI Studio)
1. Go to aistudio.google.com/apikey → Create API key. This is free within Google's generous free tier.
2. Open Anchor → ⚙ Settings → paste it into "Google AI Studio API key" → Save.
3. Without a key, the chat still works using a simpler built-in keyword matcher — you'll just get less accurate categorization.

## Notes
- Your data (prayer points, affirmations, habits, goals, todos) is stored only in this browser on this phone. It won't sync to another device or browser.
- Your API key is stored the same way — locally, never sent anywhere but Google's Gemini API.
- The free tier has a rate limit (requests per minute/day) — if you hit it, the chat automatically falls back to the local keyword matcher for that message.
- If you ever want to reset everything, clearing Chrome's site data for this page wipes it clean.
